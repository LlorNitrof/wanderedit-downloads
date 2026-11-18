# Installing WanderEdit

WanderEdit edits your travel videos on your own computer: captions, cuts, pop-up pictures and your brand kit, plus speech to text. It's free. You need **Windows 10 or 11**.

## 1. Download

Download **WanderEdit Setup** from our downloads page:
https://github.com/LlorNitrof/wanderedit-downloads/releases/latest

Only download WanderEdit from this page.

## 2. Check that it's the real file (optional, 1 minute)

Each download has a fingerprint next to it (the `.sha256` file). To check it:

1. Open **PowerShell** (Start menu → type `PowerShell`).
2. Type the line below, change the path to where you saved the file, and press Enter:

   ```
   Get-FileHash "$HOME\Downloads\WanderEdit Setup 1.0.0.exe"
   ```

3. The long code it shows must match the code in the `.sha256` file exactly.

## 3. Install

1. Double-click **WanderEdit Setup**.
2. Windows will probably say **"Windows protected your PC"**. This is expected: WanderEdit isn't signed with a paid certificate yet.
   - Click **More info**, then **Run anyway**.
   - **Only do this for WanderEdit downloaded from our page above.** For files from anywhere else, keep the warning's advice.
3. Follow the installer. You don't need an administrator password: it installs for you only.

## 4. Add your free Groq key (once)

WanderEdit uses Groq to hear what is said in your videos. It's free.

1. Go to https://console.groq.com/keys, sign up or sign in, and click **Create API Key**. Copy the key.
2. In WanderEdit, open **Settings** → **Your keys**, paste it into **Groq key**, and click **Save keys**.

**Optional:** for stock pop-up pictures, get a free key at https://pixabay.com/api/docs/ (sign in; it's under "Your API key") and paste it into **Pixabay key**.

Your keys are stored encrypted on your computer. Never share them in chats or emails.

## 5. Use it

- **Edit video:** drop a raw clip in, pick a style, and wait for ✓ Done.
- **Speech to text:** drop in a voice note or a video and get the text.
- **Transcript:** fix or cut words in a finished video, then get a new edit.
- Finished files appear in **Videos\WanderEdit**. Change the folder in Settings.

Your computer does the editing, so keep WanderEdit open until your video is done. Closing it is safe: the video starts again the next time you open WanderEdit.

## Updates

WanderEdit checks for a new version when it starts and asks before restarting to install it.

## Uninstalling

Use **Settings → Apps → WanderEdit → Uninstall**. Your videos in the WanderEdit folder are kept.
