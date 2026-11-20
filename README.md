# Jarvis

A personal AI assistant for Windows. Talk to it or type, and it answers out loud,
searches the web, remembers things about you, looks at your screen, and controls your PC.

## ⬇ [Download Jarvis for Windows](https://github.com/BBPlayzGG/jarvis-releases/releases/latest/download/Jarvis-Setup.exe)

Windows 10 or 11 (64-bit). About 120 MB. Free; you bring your own AI key (Groq has a free tier).

---

## How to install (step by step)

### 1. Download the installer
Click **[Download Jarvis for Windows](https://github.com/BBPlayzGG/jarvis-releases/releases/latest/download/Jarvis-Setup.exe)**. You'll get a file called **Jarvis-Setup.exe**.

Your browser may say the file "isn't commonly downloaded". That's normal for small apps that aren't from a big company:
- **Edge:** click **⋯** next to the download, then **Keep**, then **Show more**, then **Keep anyway**.
- **Chrome:** click **Keep** (or **Download anyway**).

### 2. Run the installer
Open **Jarvis-Setup.exe** from your Downloads folder.

If a blue box says **"Windows protected your PC"**, click **More info**, then **Run anyway**. (This appears because the app isn't code-signed; you'll only see it once.)

There's no setup wizard: Jarvis installs in a few seconds and opens by itself. It adds a **Jarvis** shortcut to your desktop and Start menu.

### 3. Get a free AI key
Jarvis needs a key for its "brain". The free option is Groq:

1. Go to **[console.groq.com/keys](https://console.groq.com/keys)** and sign in (Google or GitHub works).
2. Click **Create API Key**, give it any name, and **copy** the key (it starts with `gsk_`).

Optional extras:
- **Claude** (smartest, pay-as-you-go): create a key at **[console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)**. Your Anthropic account needs credits.
- **Fish Audio** (a natural-sounding voice): sign in at **[fish.audio](https://fish.audio)** and create an API key in your account's API settings. Without it, Jarvis uses a built-in Windows voice.

### 4. Paste your key into Jarvis
The **Settings** window opens automatically the first time.

1. Type your name if you like.
2. Under **AI brain**, pick **Groq** (or **Claude**) and paste your key.
3. If you have a Fish Audio key, paste it under **Voice**, then search for a voice you like (try "butler" or "british"), click **Use**, and press **Save & test voice**.
4. Click **Save**.

Your keys are encrypted and stay on your PC.

### 5. Allow the microphone
The first time you talk, Windows may ask for microphone access; click **Allow**.

If Jarvis can't hear you: open Windows **Settings → Privacy & security → Microphone** and turn on **Microphone access** and **Let desktop apps access your microphone**.

### 6. Talk to Jarvis
- Press **Ctrl + Alt + J** from anywhere (or click the mic button) and just speak. Jarvis sends it when you stop talking.
- Turn on **Wake word** and say **"Jarvis, …"** to talk hands-free.
- Or type in the box at the bottom.

When the Jarvis window is in the background, a small orb pops up in the bottom-right corner of your screen while it's listening and talking.

Things to try: *"What's the weather?"*, *"Open Spotify"*, *"Set the volume to 30%"*, *"What's on my screen?"*, *"Remind me in 10 minutes to check the oven"*, *"Remember that my favourite team is Arsenal."*

---

## Updates
Jarvis updates itself. When a new version has downloaded, a green **Update ready · Restart** button appears at the top of the window. Click it (or just quit and reopen Jarvis) to install it.

Your settings, keys, memory and chat history are kept through every update.

## Good to know
- **Closing the window** hides Jarvis to the system tray (bottom-right, near the clock). Right-click the tray icon and choose **Quit Jarvis** to close it fully.
- **Esc** or clicking the orb stops Jarvis talking.
- Tick **Start Jarvis when Windows starts** in Settings to have it always ready.
- By default, Jarvis asks before it runs a command, changes a file, or shuts down your PC. You can turn that off in Settings.

## Uninstall
Windows **Settings → Apps → Installed apps → Jarvis → Uninstall**.
Your settings and memory are left in `%APPDATA%\Jarvis` in case you reinstall; delete that folder to remove everything.
