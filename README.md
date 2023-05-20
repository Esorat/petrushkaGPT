# petrushkaGPT🤖

This project demonstrates how to integrate ChatGPT, a language model developed by OpenAI, with a Telegram bot in a Node.js environment. The bot can accept text or voice prompts from users and generate responses using the ChatGPT model.

## Prerequisites

Before running the project, ensure that you have the following prerequisites installed:

- Node.js: Make sure you have Node.js installed on your machine. You can download it from the official website: https://nodejs.org

- Telegram Bot Token: Obtain a Telegram Bot Token by creating a bot on the Telegram platform. Refer to the Telegram Bot API documentation for instructions on creating a bot and obtaining the token: https://core.telegram.org/bots/api

- OpenAI API Key: Sign up for the OpenAI API and obtain an API key. You can sign up for an API key at: https://www.openai.com
- Telegram API: talk with https://t.me/BotFather

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Esorat/petrushkaGPT.git
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-directory>
   ```

3. Configure the application by create in config folder production.json and default.json
add to this json your api key for Telegram and OpenAi like this:
 ```bash
{
  "TELEGRAM_TOKEN": "bla-bla your key here",
  "OPENAI_KEY": "bla-bla your key here"
}
   ```


4. 
```bash
npm i
```
5. Start locally in your machine:
   ```bash
   npm run dev
   ```
 (Will start in Dev mode)
  

## Usage

To run the application, use the following command:

Locally: 

```bash
npm i
```
Docker:
```bash
docker build -t tgbot .
```
```bash
make run
```

The Telegram bot will be up and running, ready to accept text or voice prompts from users.

## Bot Commands

The Telegram bot supports the following commands:

- `/new`: Start a new conversation with the bot.
- `/start`: Start a new conversation with the bot.

## Text Prompts

To send a text prompt or voice  to the bot, simply type a message and send it to the bot. The bot will generate a response using ChatGPT and send it back to you.

## Voice Prompts

To send a voice prompt to the bot:

1. Press the microphone icon in the chat window.
2. Record your voice message.
3. Release the microphone icon to send the voice message.
4. The bot will transcribe the voice message, generate a response using ChatGPT, and send it back to you.

## Customization

Feel free to customize and extend the project according to your requirements. You can modify the behavior of the bot, add additional commands, or integrate other features. Refer to the Telegraf and OpenAI documentation for more information:

- Telegraf: https://telegraf.js.org
- OpenAI API: https://www.openai.com/docs/api-reference/introduction

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per the terms of the license.
