<div align="center">

# 💬 ft_irc

### A multi-client IRC server and interactive moderation bot in C++98

A 42 School networking project that implements an IRC-style server using TCP sockets and `poll()`. Connect with an IRC client, join channels, exchange messages, and manage channel settings.

</div>

## ✨ Features

- 🌐 Multiple simultaneous client connections
- 🔐 Password-protected server access
- 💬 Channels, private messages, topics, and user lists
- 🛠️ IRC commands including `JOIN`, `PART`, `NICK`, `PRIVMSG`, `MODE`, `KICK`, `TOPIC`, `WHO`, and `WHOIS`
- 🤖 Optional bot that monitors nicknames and channel messages for configured inappropriate words
- 📦 DCC command support

## ⚙️ Build and run

Build the server:

```bash
make
./ircserv <port> <password>
```

Connect from an IRC client such as Irssi:

```text
/connect localhost <port> <password>
```

Build and start the optional bot in a second terminal:

```bash
make bonus
./ircbot 127.0.0.1 <port> <password>
```

## 🧰 Tech stack

`C++98` · TCP/IP sockets · `poll()` · POSIX threads · IRC protocol

## 👩‍💻 Profile

- GitHub: [@sakkayaa](https://github.com/sakkayaa)
- LinkedIn: [Sedef Akkaya](https://www.linkedin.com/in/sedef-akkaya-0a5580228/)
