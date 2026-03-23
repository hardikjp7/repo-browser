# 🔍 GitHub Repo Browser

> Browse, copy, and download GitHub repositories — even when GitHub is blocked on your network.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](https://hardikjp7.github.io/repo-browser/)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20With-HTML-orange?style=for-the-badge)](index.html)

---

## 🧩 What Is This?

**GitHub Repo Browser** is a single-page web tool that lets you browse any public GitHub repository directly in your browser — no GitHub access required.

If you work in an organization where GitHub is blocked (like many corporate networks), this tool acts as a lightweight proxy viewer. You can explore repo contents, read files, copy code, and download files — all without ever visiting `github.com`.

---

## ✨ Features

- 📂 **Browse any public GitHub repository** — Enter a repo URL and explore its full file structure
- 📄 **View file contents** — Read source code and files directly in the browser
- 📋 **Copy code** — Copy file contents to your clipboard with one click
- ⬇️ **Download files** — Save individual files to your machine
- 🚫 **No GitHub access needed** — Works even when `github.com` is blocked on your network
- 💡 **Zero setup** — It's just one `index.html` file, no installation or backend required

---

## 🚀 How to Use

### Option 1: Use the Hosted Version
Just open the live site in your browser:

👉 **[hardikjp7.github.io/repo-browser](https://hardikjp7.github.io/repo-browser/)**

### Option 2: Host It Yourself
If the hosted version is also blocked, you can self-host it easily:

1. Download `index.html` from this repo (or get it from a colleague who has access)
2. Open it in any modern web browser — no server needed
3. Enter any public GitHub repository URL and start browsing

---

## 🖥️ How It Works

This tool uses the **GitHub API** (`api.github.com`) to fetch repository data and file contents. In many corporate networks, `api.github.com` remains accessible even when `github.com` itself is blocked — this tool takes advantage of that to give you access to repo contents.

```
You → GitHub Repo Browser → api.github.com → Repository Files
```

> **Note:** Only **public repositories** are supported. Private repos require authentication which is not supported in this tool.

---

## 📁 Project Structure

```
repo-browser/
└── index.html     # The entire app — just one file!
```

---

## ⚠️ Limitations

- Works only with **public repositories**
- Requires access to `api.github.com` (not `github.com`)
- GitHub API has a **rate limit of 60 requests/hour** for unauthenticated usage
- Not suitable for cloning or downloading entire repositories at once

---

## 🙌 Why I Built This

GitHub is blocked on many corporate networks. As a developer, not having access to GitHub means not being able to reference code, read documentation, or grab a utility snippet when you need it most.

This tool was built as a simple workaround — a single HTML file that you can open anywhere and still get your work done.

---

## 📄 License

Licensed under the [Apache 2.0 License](LICENSE).

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for improvements or run into issues, feel free to open an issue or submit a pull request.

---

<p align="center">Made with ❤️ for developers stuck behind firewalls</p>
