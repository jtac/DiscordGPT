# DiscordGPT Bot

## Description
DiscordGPT is a versatile Discord bot powered by OpenAI's GPT-4 and Google's Custom Search API. It is capable of conducting searches based on user input, providing summaries of search results, and engaging in interactive text-based conversations with users. 

## Features

1. **Google Search Integration**: DiscordGPT Bot is integrated with Google's Custom Search API. Users can request searches with a simple command, and the bot will retrieve and display the first search result.

2. **Information Summarization**: For any search result it retrieves, the bot generates a concise summary of the content using GPT-4. It also converts any imperial units in the text to metric SI units, and wind speed is indicated in m/s.

3. **Interactive Conversations**: The bot can engage in text-based conversations with users, responding to their messages in a witty and creative manner.

## Setup

### Prerequisites
To run this bot, you will need:

- Python 3.7 or later.
- A Discord account and server where the bot will be deployed.
- An OpenAI account with access to the GPT-4 API.
- A Google account with access to the Custom Search API.

### Environment Variables
You will need to set the following environment variables:

- `DISCORD_TOKEN`: Your Discord bot token.
- `OPENAI_API_KEY`: Your OpenAI API key.
- `OPENAI_API_TYPE`: The type of OpenAI API you're using, in this case "azure".
- `AZURE_ENDPOINT_URL`: The Azure endpoint URL for OpenAI.
- `OPENAI_API_VERSION`: The version of the OpenAI API you're using.
- `GOOGLE_API_KEY`: Your Google API key.
- `GOOGLE_ENGINE_ID`: Your Google Custom Search Engine ID.

You can load these environment variables using a package like `python-dotenv`, or manually add them to your environment.

## Usage

Once the bot is running, you can interact with it in the following ways:

- **Search**: Type `!search <query>` to conduct a Google search. The bot will return a summary of the first result.

- **Chat**: Mention the bot in a message to start a conversation. The bot will respond in a brief, informative manner.

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Remember that using this bot implies compliance with OpenAI's use case policy.
