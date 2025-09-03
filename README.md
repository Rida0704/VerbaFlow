# AudioWiz

### Multilingual Live Video conferencing

# Description

Live Video Conferencing app which transcribes, translates and speaks out the text to all users on the call in realtime. Also provides with the meeting minutes/summary of the meeting.

# Tech Stack

- NextJS
- Typescript
- Livekit
- Pusher
- Deepgram Nova AI
- tRPC
- TailwindCSS
- Prisma
- MySQL

# Installation Steps

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   ```

2. cd into the project directory

3. Install dependencies and run:
   ```bash
   npm i
   npm run dev
   ```

Note: Populate env vars by copying the .env.example file

# Libraries and Dependencies

```json
"dependencies": {
"@headlessui/react": "^1.7.14",
"@livekit/components-react": "^0.7.3",
"@livekit/components-styles": "^0.3.1",
"@next-auth/prisma-adapter": "^1.0.5",
"@prisma/client": "^4.11.0",
"@tanstack/react-query": "^4.28.0",
"@trpc/client": "^10.18.0",
"@trpc/next": "^10.18.0",
"@trpc/react-query": "^10.18.0",
"@trpc/server": "^10.18.0",
"@vitalets/google-translate-api": "^9.1.0",
"axios": "^1.3.5",
"google-translate-api-browser": "^3.0.1",
"livekit-client": "^1.7.1",
"livekit-server-sdk": "^1.1.4",
"next": "^13.2.4",
"next-auth": "^4.21.0",
"openai": "^3.2.1",
"pusher": "^5.1.2",
"pusher-js": "^8.0.2",
"react": "18.2.0",
"react-dom": "18.2.0",
"react-icons": "^4.8.0",
"superjson": "1.12.2",
"transliteration": "^2.3.5",
"zod": "^3.21.4"
},
```

# Key Features

This multilingual video conferencing application addresses several critical challenges in real-time communication:

- **Low Latency**: Achieved 4-5 seconds latency (sometimes even 3 seconds) compared to the previous 10-15 seconds
- **Cross-Browser Compatibility**: Works on all browsers without relying on browser-specific APIs
- **High Accuracy Transcription**: Uses Deepgram's Nova AI for state-of-the-art transcription accuracy
- **Real-time Translation**: Provides instant translation and text-to-speech in multiple languages
- **Meeting Summaries**: Automatically generates meeting summaries in the user's native language
- **Dynamic Language Switching**: Allows users to change languages during active meetings
