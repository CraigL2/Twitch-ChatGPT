![Twitch Status](https://img.shields.io/twitch/status/90s_Craig?style=social) ![Mastodon Follow](https://img.shields.io/mastodon/follow/109502511665426028?domain=https%3A%2F%2Fpb.craignt.com&style=social)

# Twitch-ChatGPT: A Customizable Twitch Chat Bot Integrated with Streamer.bot (0.2.0)

Welcome to Twitch-ChatGPT, your go-to **AI Chat Bot for Twitch** designed to enhance streamer-viewer interactions through dynamic and personalized responses. This **Intelligent Twitch Chat Interaction** tool is powered by ChatGPT and seamlessly integrated with Streamer.bot, providing a unique solution for lively and engaging Twitch streams.

Twitch-ChatGPT is not just another **Twitch Chat Bot**; it's a doorway to a more interactive and spontaneous streaming experience, bringing a breath of fresh air from the usual canned responses.

## 💬 Get Support on Discord

Encountered an issue or have a brilliant idea to share? We'd love to hear from you! Join the [90s Craig Discord Server](https://discord.gg/bYDxFf3akk) where I'd be more than happy to assist and discuss. Whether you need help with setup, want to share your exciting new use case, or discuss potential features, the #tech-and-ai channel is the place to connect and get the support you need. So, don't hesitate, [join us on Discord](https://discord.gg/bYDxFf3akk) and be part of the community!

## 🤖 Live Demo: Experience the Dynamic Twitch Chat Bot
Test drive Twitch-ChatGPT live on my Twitch page:
- **URL:** [https://www.twitch.tv/90s_craig](https://www.twitch.tv/90s_craig)
- **Chat Command:** `!askcraig how are you today robot?`

## 🚀 Features: More Than Just a Customizable Twitch Bot
Twitch-ChatGPT boasts a plethora of features ensuring a rich and **Automated Twitch Chat Moderation** and interaction, including:
- Discord go-live notification
- Twitch chat response
- Twitch cheer events response
- Twitch follow response
- Twitch sub/re-sub/gift sub response
- Twitch raid announcement
- Bot timeout (via channel points redemption)
- Backseat warning (via chat/whisper command)
- Language warning (on predefined inappropriate words)
- Response Length Control (control response length via `outputLength` variable)

## 💡 Why Choose Twitch-ChatGPT?
With Twitch-ChatGPT, you're not just getting a bot; you're elevating your Twitch streams with **Intelligent Twitch Chat Interaction**. Break free from the monotony of canned responses and embrace the dynamic, context-aware responses generated by ChatGPT, tailored to boost viewer engagement and overall stream quality.

## 📋 Prerequisites
Ensure you are ready to set up Twitch-ChatGPT:
- A valid Twitch account.
- Streamer.bot installed and set up.
- Access to ChatGPT and a [valid OpenAI Key](https://platform.openai.com/account/api-keys).

## 🛠 Installation: Streamer.bot Twitch Integration Made Easy

1. **Import Actions to Streamer.bot:**
    ```bash
    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    
    ```

3. **Follow the on-screen prompts to import the actions.**

4. **Update Actions and Variables:**
    - **_ChatGPT API Handler:**
        - Set `chatGPT3APIkey` to your [OpenAI API key](https://platform.openai.com/account/api-keys).
        - Set `model` to `gpt-3.5-turbo` or `gpt-4`.
        - Update `behavior` to match your chatbot's personality.
    - **Discord.Go Live:**
        - Set `inputGPT` to prompt GPT for a live announcement.
        - Set `discordWebHookUrl` to your Discord webhook URL.
    - **All Other Actions:**
        - Set `outputLength` to your desired response character count.

5. **Create a Chat Command:**
    - E.g., `!chatGPT` or add a trigger for `@ChatBotsName`.

6. **Connect Actions to Events:**
    - (More details may be provided later)

## 🤝 Contribution: Enhancing the OpenAI GPT-3/GPT-4 Twitch Bot
Contributions, issues, and feature requests are welcome! Check the issues page to see how you can contribute to this **Customizable Twitch Bot** project.

## 📝 To-Do List
- More customization for chat prompts
- Custom character limits by event type
- Fix occasional funky text in ChatGPT responses
- Twitch Shout Out Integration

## 📌 Notes
- Customize TTS implementation to suit your needs, this is likely broken in the current state.
- I am not a professional programmer; this project is a compilation and adaptation of beneficial resources.

## 💵 Costs
Engage with Twitch-ChatGPT at minimal costs associated with OpenAI API usage:
- `gpt-3.5-turbo`: $0.002 per 1K tokens for Completion and prompt
- `gpt-4`: $0.06 per 1K tokens for Completion and $0.03 per 1K tokens for prompt
- [Get an API key on the OpenAI Platform](https://platform.openai.com/account/api-keys)

## 🛑 Troubleshooting: Smooth Streamer.bot Twitch Integration
- **gpt-4 API Access:** No OpenAI Plus account needed, but [bill at least $1 on gpt-3.5-turbo API to access gpt-4 API](https://help.openai.com/en/articles/7102672-how-can-i-access-gpt-4).
- **`temperature` Variable:** Format as "0.9", not "0,9".
- Further support is available on the [90s Craig Discord Server](https://discord.gg/bYDxFf3akk) in the #tech-and-ai channel

## 🙏 Credits
- [Streamer.bot](https://streamer.bot)
- [LeBluxTV](https://www.twitch.tv/lebluxtv)
- [Raith](https://about.raith.one)
- [StreamUp.tips](https://streamup.tips)
