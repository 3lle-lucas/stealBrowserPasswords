# 🛡️ stealBrowserPasswords

A simple tool to extract saved passwords from Chromium-based browsers and send them to a Discord channel. Built for **security research** and **educational purposes only**, not for shady stuff.
This is the first release of a bigger project 👾
You can grab it and integrate it into your own ethical security research setups.

## 👀 Demo

https://github.com/user-attachments/assets/324d1b4c-f5bc-43b5-aaba-e63d66f75a28

## ❓ Why Discord?

Honestly? Because it’s kinda cool. Sure, the Discord API has some limits, but it’s a convenient way to receive logs in real-time. Plus, Discord is rarely blocked in corporate environments... not that you should use it there! (Seriously, **don’t do anything dumb.**)

## ⚙️ How does it work?

- Extracts encrypted passwords from the browser’s SQLite database.

- Decrypts them using built-in Windows APIs.

- Sends them to a specified Discord channel via Invoke-RestMethod.

- The decryption of the passwords will be another module, with a simple python script you can do by your own.

⚠️ First time using PowerShell, so be gentle! 😉

## 🚨 Disclaimer

This tool is provided strictly for educational and research purposes. I am not responsible for any misuse. Unauthorized access to systems and data is illegal. Use this responsibly and only in environments where you have explicit permission.

👾 **Enjoy hacking (ethically)!** If you find bugs or have suggestions, feel free to contribute!

💬 **Join the community!** Have questions or want to chat? Join my Discord server: [Join here](https://discord.com/invite/ZRf5PJYGMk)

