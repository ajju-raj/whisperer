# Whisperer

Whisperer is a simple AI-powered web application that uses OpenAI's Whisper API to transcribe and summarize audio files. Developed with Next.js, it allows users to upload `.wav` or `.mp3` audio files, which are then processed, and a summary of the audio is displayed.

## Features

- Upload `.wav` and `.mp3` audio files
- Use OpenAI's Whisper API for transcription and summarization
- Display the summary of the uploaded audio
- Built with Next.js and can be deployable on Vercel

## Tech Stack

- **Frontend**: Next.js, React.js
- **Backend**: OpenAI API (Whisper)
- **Deployment**: Vercel

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/ajju-raj/whisperer.git
   cd whisperer
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root directory and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   The app will be running at `http://localhost:3000`.

## Deployment

Whisperer can be easily deployed on [Vercel](https://vercel.com/).

1. Push your code to a GitHub repository.
2. Connect your GitHub repository to Vercel.
3. Deploy the project from the Vercel dashboard.

## Usage

1. Open the app in your browser.
2. Upload a `.wav` or `.mp3` audio file using the file input.
3. Click on the "Upload" button to send the file for transcription and summarization.
4. The summary will be displayed on the screen once processing is complete.

## Project Structure

- `pages/index.tsx`: Main page with file upload functionality.
- `api`: Backend route to handle file uploads and API calls to OpenAI's Whisper.

## Contributing

Feel free to open issues or submit pull requests with improvements or new features.

## License

This project is licensed under the MIT License.

## Acknowledgements

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
