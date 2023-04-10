# 🌐 cmd:// Protocol
A simple `cmd://` protocol which runs commands in your terminal through your browser.

## 🖱️ Setting Up
1. Download the [repository](https://github.com/cmd-protocol/cmd-protocol/archive/refs/heads/main.zip) files.
2. Extract the zip file.
3. Open the extracted folder and then click on `cmd-protocol-main` folder.
4. Run the `setup.bat` file and when asked for Administrator privileges, click `Yes`.
    - The batch file registers the registry values stored in `register.reg` and copies the `cmd.exe` file to the required file location.
5. Try it out!
    - In your browser, in the URL bar, type something like [`cmd://help`](cmd://help) and run the protocol.

## ⚠️ Warning
Websites may use this protocol maliciously, so if you ever get a pop-up for it when you didn't run it voluntarily, click `Cancel` so the command doesn't run.

But don't worry if you click open, the executable will still ask for a confirmation before running the command.
