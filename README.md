# Chatter Coding Challenge 🤖

&nbsp;
# Goals / Outcomes ✨
- To test knowledge of using sockets (socket.io) and events
- Understanding of callbacks, hooks and function references

&nbsp;
# Requirements 📖
Most of the work needs to be done in the `Messages` components.

- Implement hooks to handle events
- Scroll to the bottom of the messages list when sending/receiving a message
- Show the initial Botty message by default
- Use **sockets** to:
  - Send the user's message to Botty
  - Show a typing message when Botty is typing
  - Handle incoming Botty messages and display them

&nbsp;
# Botty Socket Events
See the [Botty server](https://github.com/alexgurr/botty) documentation for more information.
- `bot-typing`: Emitted by Botty when they are typing in response to a user message.
- `bot-message`: Emitted by Botty with a message payload in response to a user message.
- `user-message`: Emitted by you/the client with a messsage payload

&nbsp;
# Screenshots 🌄
&nbsp;
![screenshot-desktop](https://puu.sh/Hp0C2/cb14e843de.png)
<img alt="screenshot-mobile" width=400 src="https://puu.sh/HoYEw/9b760f91f7.png" />
