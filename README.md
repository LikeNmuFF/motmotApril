<div align="center">

<!-- ═══════════════════════════════════════════════════════════
     WAVE HEADER — animated gradient banner
════════════════════════════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Monthsary%20Website%20💕&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=A%20romantic%20one-page%20love%20letter%20built%20in%20HTML&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

<!-- ═══ TYPING ANIMATION ═══ -->
<img src="https://readme-typing-svg.demolab.com?font=Sacramento&size=36&duration=3500&pause=800&color=C9617A&center=true&vCenter=true&multiline=false&width=600&height=70&lines=Happy+Monthsary+%F0%9F%8C%B8;Built+with+love+%E2%99%A5;For+the+one+who+matters+most;Every+moment+with+you...;...is+my+favourite+%F0%9F%8C%BA" alt="Typing SVG" />

<br/>

<!-- ═══ BADGES ═══ -->
<img src="https://img.shields.io/badge/Made%20with-Love%20%E2%99%A5-c9617a?style=for-the-badge&labelColor=5c1a2e" />
&nbsp;
<img src="https://img.shields.io/badge/HTML-Single%20File-e8a0b0?style=for-the-badge&logo=html5&logoColor=white&labelColor=c9617a" />
&nbsp;
<img src="https://img.shields.io/badge/No%20Framework-Pure%20JS-c9a96e?style=for-the-badge&labelColor=5c1a2e" />
&nbsp;
<img src="https://img.shields.io/badge/Mobile-Friendly-fce8ee?style=for-the-badge&labelColor=c9617a&color=e8a0b0" />

<br/><br/>

</div>

---

<div align="center">

## 🌸 &nbsp; What is this?

</div>

A **single-file romantic website** you can send to your girlfriend on your monthsary — or any special occasion. Drop it in a folder with your photos and a song, fill in the config block at the top, and it's ready to share. No build tools. No dependencies. Just love.

---

<div align="center">

<!-- ═══ ANIMATED FEATURE SNAKE ═══ -->

## ✨ &nbsp; Features

</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Jost&weight=300&size=15&duration=2000&pause=400&color=C9617A&center=true&vCenter=true&multiline=true&width=700&height=130&lines=%F0%9F%8C%B8+Falling+petal+canvas+animation;%F0%9F%8E%B5+Music+prompt+modal+with+fade-in+audio;%F0%9F%93%B8+Masonry+gallery+with+lightbox+%26+keyboard+nav;%F0%9F%92%8B+%22Send+a+Kiss%22+button+with+floating+hearts;%E2%9C%A8+Confetti+burst+on+page+load;%F0%9F%93%85+Auto+month+counter+from+your+start+date" alt="Features" />
</div>

<br/>

|     | Feature              | Details                                                   |
| --- | -------------------- | --------------------------------------------------------- |
| 🌸  | **Petal Rain**       | Canvas-based falling petals, always in the background     |
| 🎵  | **Music Prompt**     | Polite modal asks before playing — fade-in audio          |
| 📸  | **Photo Gallery**    | Masonry grid, hover captions, full lightbox viewer        |
| 💋  | **Send a Kiss**      | Button launches floating hearts + rotating sweet messages |
| 🎉  | **Confetti Burst**   | Fires automatically 1.8s after page load                  |
| 📅  | **Month Counter**    | Calculates months since your start date automatically     |
| 📱  | **Responsive**       | Works beautifully on mobile and desktop                   |
| ⚙️  | **One Config Block** | All personalisation in one place at the top of the script |

---

## 🗂️ &nbsp; File Structure

```
your-folder/
│
├── index.html       ← the entire website (this file)
│
├── song.mp3         ← your background music
│
├── photo1.jpg       ← gallery photo 1  (hero tile)
├── photo2.jpg       ← gallery photo 2
├── photo3.jpg       ← gallery photo 3
├── photo4.jpg       ← gallery photo 4  (tall tile)
├── photo5.jpg       ← gallery photo 5
└── photo6.jpg       ← gallery photo 6  (wide tile)
```

> 💡 You can add as many photos as you like — just extend the `photos` array in CONFIG.

---

## ⚙️ &nbsp; Setup — 3 Steps

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Jost&weight=200&size=14&duration=1800&pause=300&color=C9A96E&center=true&vCenter=true&multiline=false&width=500&height=40&lines=Step+1+%E2%86%92+Edit+CONFIG+%7C+Step+2+%E2%86%92+Add+your+files+%7C+Step+3+%E2%86%92+Open+%26+share" alt="Steps" />
</div>

<br/>

### Step 1 — Edit the CONFIG block

Open `index.html` and find the `CONFIG` object near the top of the `<script>` tag. It looks like this:

```js
const CONFIG = {
  /* ── Names ── */
  herName: "Sofia", // ← her name
  yourName: "Marco", // ← your name

  /* ── Relationship start date ── */
  startDate: "2024-10-24", // ← YYYY-MM-DD format

  /* ── Music ── */
  music: {
    file: "song.mp3", // ← your audio filename
    title: "Perfect — Ed Sheeran", // ← shown in the music modal
  },

  /* ── Gallery photos ── */
  photos: [
    { file: "photo1.jpg", caption: "The day it all began 🌸" },
    { file: "photo2.jpg", caption: "Always smiling with you 💕" },
    { file: "photo3.jpg", caption: "Favourite place 🌙" },
    { file: "photo4.jpg", caption: "Just us ♥" },
    { file: "photo5.jpg", caption: "Pure happiness 🌺" },
    { file: "photo6.jpg", caption: "My favourite view 🌅" },
    // add more lines here as needed!
  ],
};
```

### Step 2 — Add your files

Put your `song.mp3` and all your `photo*.jpg` files in the **same folder** as `index.html`. That's it — no paths to configure.

> Supported audio: `.mp3`, `.ogg`, `.wav`  
> Supported images: `.jpg`, `.jpeg`, `.png`, `.webp`, `.gif`

### Step 3 — Open & share

Double-click `index.html` to open it in any browser. To share it:

- **Local sharing** — Send the whole folder as a `.zip`
- **Quick hosting** — Drag the folder into [Netlify Drop](https://app.netlify.com/drop) for a free instant link
- **GitHub Pages** — Push to a repo, enable Pages, share the URL

---

## 🎨 &nbsp; Customisation

<details>
<summary><b>💬 Edit the love message & reasons</b></summary>
<br/>

Search for `Why I love you` in the HTML. You'll find:

- **4 reason cards** — edit the `<p class="reason-text">` inside each `.reason-card`
- **The paragraph** — edit the `<blockquote class="message-paragraph">` text

</details>

<details>
<summary><b>🎨 Change the colour theme</b></summary>
<br/>

All colours are CSS variables at the very top of the `<style>` block:

```css
:root {
  --rose: #c9617a; /* primary pink */
  --rose-light: #e8a0b0; /* soft pink    */
  --gold: #c9a96e; /* gold accent  */
  --cream: #fdf6f0; /* background   */
  --deep: #5c1a2e; /* dark rose    */
}
```

</details>

<details>
<summary><b>📸 Add more than 6 photos</b></summary>
<br/>

Just add more entries to `CONFIG.photos`:

```js
photos: [
  { file: "photo1.jpg", caption: "Our first date 🌸" },
  { file: "photo2.jpg", caption: "The beach trip 🌊" },
  { file: "photo3.jpg", caption: "Movie night 🎬"    },
  // ...keep going!
],
```

The gallery grid adapts automatically.

</details>

<details>
<summary><b>💬 Edit the footer quote</b></summary>
<br/>

Search for `footer-quote` in the HTML and change the text inside that paragraph to any quote you love.

</details>

---

## 🌐 &nbsp; Browser Support

| Browser          | Support |
| ---------------- | ------- |
| Chrome / Edge    | ✅ Full |
| Firefox          | ✅ Full |
| Safari (iOS)     | ✅ Full |
| Samsung Internet | ✅ Full |

> ⚠️ Audio autoplay is blocked by all modern browsers — that's why the music modal exists. It gives a user gesture (button click) which unlocks audio playback.

---

<div align="center">

<!-- ═══ FOOTER WAVE ═══ -->

<br/>

_"I have found the one whom my soul loves."_
_— Song of Solomon 3:4_

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Sacramento&size=30&duration=4000&pause=1000&color=C9617A&center=true&vCenter=true&width=400&height=60&lines=Made+with+%E2%99%A5;Yours+forever" alt="Footer typing" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
