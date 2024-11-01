# Roasted

This project uses [Stagehand](https://github.com/browserbase/stagehand) by [Browserbase](https://browserbase.com) to automate the browser to roast a given Github profile.

## Features

- **GitHub Profile Roasting**: Enter your GitHub profile URL and get a funny roast based on your profile.
- **Dynamic Loading Messages**: Enjoy a series of humorous loading messages while your roast is being prepared.
- **Copy to Clipboard**: Easily copy your roast to the clipboard with a single click.

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alanagoyal/roasted.git
   cd roasted
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add your API keys:

   ```plaintext
   OPENAI_API_KEY="your-openai-api-key"
   ANTHROPIC_API_KEY="your-anthropic-api-key"
   BROWSERBASE_API_KEY="your-browserbase-api-key"
   BROWSERBASE_PROJECT_ID="your-browserbase-project-id"
   ```

### Run

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application in action.

## Deploy 

Deploy using [Vercel](https://vercel.com)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
