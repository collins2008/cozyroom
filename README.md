# cozyroom
A lightweight, real-time P2P cinema and virtual hangout space. Built with WebRTC.
# 🎬 Vibe Space

A lightweight, pure frontend Peer-to-Peer virtual hangout and cinema room. Built to survive bad networks and deliver crystal-clear vibes.

No heavy servers, no database, no complex backend. Just a single file powered by WebRTC and pure JavaScript magic. Drop in, share a link, and watch movies with your friends.

## ✨ The Features

* **🍿 True Cinema Mode:** One click hides all the UI (buttons, local camera, chat logs) and expands the shared movie to fill the entire screen for a distraction-free watch party.
* **📡 Low-Data Survival Switch:** Built specifically to combat fluctuating networks. Hit the "Low Data" toggle to instantly kill all incoming/outgoing video streams, dedicating 100% of your bandwidth to keeping voice chat crystal clear.
* **👾 Floating Avatars:** Draggable, floating avatars represent everyone in the room. 
* **🎙️ Voice Activity Glow:** Avatars pulse with a neon glow when someone is speaking, powered by a lightweight Audio Analyser.
* **💬 Thought Bubbles:** Real-time chat messages pop up directly over your avatar's head as a thought bubble, so you don't have to look away from the movie to read the chat.
* **🔊 System Audio Sharing:** When you share your screen, the app specifically hooks into the tab's system audio so your friends hear the movie directly, not through your laptop mic.

## 🛠️ The Tech Stack

* **Frontend:** Vanilla HTML5, JavaScript, and Tailwind CSS (via CDN).
* **Network / Real-Time:** WebRTC API managed by [PeerJS](https://peerjs.com/) for mesh networking and data channels.
* **Hosting:** GitHub Pages.

## 🚀 How to Use It

1. **Deploy:** Fork this repo and enable GitHub Pages in your repository settings.
2. **Enter the Space:** Go to your live URL, pick an avatar, put in your name, and hit "Enter Space".
3. **Invite Friends:** Click the **"Copy Invite Link"** button in the top left. Send that unique URL to a friend.
4. **Watch a Movie:** Click the purple Screen Share button in the bottom dock. **Important:** Select a specific *Chrome Tab* and ensure **"Share tab audio"** is checked so your friends can hear the movie!

## 🤝 Notes
Because this uses a free public PeerJS signaling server and WebRTC mesh networking, it is best optimized for smaller groups (2-4 people) hanging out.
