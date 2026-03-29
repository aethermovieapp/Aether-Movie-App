<h1 align="center">Aether 🦋</h1>
<p align="center"><b>The Future of Cinematic Streaming. Built for Speed, Privacy, and Elegance.</b></p>


📖 Overview


Aether is a next-generation, account-free streaming client and paired CMS ecosystem. Designed with a stunning, glassmorphic "Liquid Interface," Aether bridges the gap between infinite TMDB metadata catalogs and your personal stream mappings. It offers a premium, ad-supported streaming experience with a robust fallback system for advanced video formats like MKV and HEVC.


✨ Key Features


• 🎨 Liquid Interface: A gorgeous, hardware-accelerated dark-mode UI utilizing fluid CSS animations and glassmorphic overlays.

• 🎬 Infinite TMDB Catalog: Dynamically fetches trending movies, top-rated classics, and live TV show season/episode structures directly from The Movie Database.

• ⚡ Smart Player Engine: Utilizes a hybrid player system. Plays standard MP4s natively on the web canvas, with an automatic fallback to Android's Native Hardware Engine or VLC Player Intent for heavy .mkv or HEVC files.

• 🔒 100% Private & Account-Free: "Continue Watching" progress and "Library" saves are stored exclusively in the user's local localStorage device cache. Zero user accounts required.

• 📡 Live OTA Updates: Push instant UI alerts, force application updates, and change AdMob configurations globally in real-time via the coupled Firebase CMS.

• 💰 Integrated Monetization: Built-in logic for @capacitor-community/admob including Rewarded Video (unlocks streams/downloads), Interstitial Overlays, and bottom Banner ads.

🏗️ Architecture & Tech Stack
• Frontend (Client & CMS): React.js (Vite), Tailwind CSS, Lucide Icons.

• Backend & Real-time Sync: Firebase (Firestore, Anonymous Authentication).

• Native Wrapper: Ionic Capacitor (Android & Web).

• Native Plugins: @capacitor/status-bar, @capacitor-community/admob, Custom Java Video Hardware Bridge.


🚀 Getting Started


1. Clone the repository.
2. Run npm install to install dependencies.
3. Add your Firebase configuration keys and TMDB API key to the App.jsx configuration block.
4. Run npm run build and npx cap sync.
5. Open Android Studio via npx cap open android to build your APK.


⚠️ Disclaimer


Aether is strictly a UI interface and mapping tool. It does not host, store, or distribute any copyright-protected media content. Users/Administrators must provide their own direct stream links (e.g., via personal cloud storage or Real-Debrid) through the CMS dashboard.
