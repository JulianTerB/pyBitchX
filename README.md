### 📄 `README.md`

# pyBitchX

A terminal IRC client made with just **pure Python**, taking inspiration from the aesthetics of BitchX and Mr. Robot.

pyBitchX is crafted to be **cross-platform**, **user-friendly**, and **educational**. It allows you to jump into IRC chat rooms globally, engage in conversations, and learn about IRC without the hassle of SSL/TLS or cumbersome dependencies.

---

## Features

- **Pure Python** – no need for external binaries
- **Plug-and-play** – clone and run easily if you have Python installed
- **Global IRC rooms** – create or join channels on Libera.chat
- **Customizable nicknames and channels** – set through `config.ini`
- **Basic terminal interface** – fast and minimal text-based interaction
- **Threaded I/O** – receive messages while typing
- **Learning-focused** – ideal for understanding the IRC protocol, networking, and terminal programming

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourname/pyBitchX.git
   cd pyBitchX
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate      # Windows
   ```

3. Launch the client:
   ```bash
   python3 main.py
   ```

> ⚠️ It's recommended to use Python 3.13 or newer. Make sure Python is already installed.

---

## Configuration

Modify `config.ini` to set up your nickname, server, and channel:

```ini
[IRC]
server = irc.libera.chat
port = 6667
nickname = fs0ciety
channel = #t3l
```

- `server`: The IRC server to connect to
- `port`: Default IRC port (usually 6667)
- `nickname`: Your chosen IRC nickname
- `channel`: Default channel you want to join

You can join other channels later or adjust the config.

---

## Usage

After starting the client:

- Type messages in the terminal to send them to your current channel
- Incoming messages are displayed asynchronously
- Use `/join #channel` to enter another room
- Use `/nick newnick` to change your nickname
- Use `/quit` to disconnect from IRC

---

## Contributing

pyBitchX is **open-source and meant for learning**. Contributions are encouraged:

1. Fork the repository
2. Create a branch for your new feature
3. Submit a pull request with a clear explanation

---

## License

pyBitchX is licensed under the **MIT License with a disclaimer**.
Refer to [LICENSE](LICENSE) for complete details.

> ⚠️ **Disclaimer:** This software is meant for **educational and ethical purposes only**. The authors do **not support or take responsibility for illegal activities**, including unauthorized access to networks, servers, or data. Users must follow all applicable laws.

---

## Notes

- Any IRC client can join the channels you create with pyBitchX (compatible across different clients)
- SSL/TLS isn't implemented yet – designed for basic IRC learning and exploration
- Built to help you understand networking, threading, and terminal user interfaces
