# DeepSeek Chat Demo Enhanced

[简体中文](README.md) · [Try the live demo](https://wenpu0425-hub.github.io/DeepSeek_Chat_Demo_Enhance/)

A browser-based extension of the [official DeepSeek Chat Demo](https://github.com/deepseek-ai/chat-demo) with global memory, conversation compression, and four levels of reasoning effort.

## Quick start

Open the live demo and enter your own DeepSeek API key under **Settings → Data**.

- **Global memory.** Save preferences in **Settings → General**, or type `/remember Reply in English by default`. Saved memory is shared across chats in the same browser profile and site.
- **Conversation compression.** Type `/compress` in a long chat. It makes an API call to summarize older messages. Later requests use that summary and recent messages. The full transcript remains visible, and global memory is sent verbatim.
- **Reasoning effort.** Use the slider below the message box to choose **Off / Low / High / Max**.

Your API key, chat history, and memory are stored in your browser. Chat history and memory stay separate across devices. You can transfer chats with the history ZIP and copy memory from Settings.

## License

[MIT](LICENSE), with the original DeepSeek copyright notice.
