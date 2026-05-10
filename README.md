# 🐾 PetOlife — Launch Home Page
### Code-A-Thon Submission · Full Stack Engineer Internship

> **"One Identity. Every Life."**  
> A high-performance launch page introducing PetOlife's Unified Pet Identity concept — connecting pet parents, veterinarians, and care records through a single trusted digital profile.

---

## 🔗 Live Site

👉 **[View Live →](https://Siddx6.github.io/petolife-launch)**

---

## 📁 Project Structure

```
petolife-launch/
├── index.html        # Complete single-file app (HTML + CSS + JS)
└── README.md         # This file
```

Zero dependencies. Zero build steps. One file.

---

## 🚀 Local Setup — Run in 30 Seconds

### Option 1: Just Open the File (Quickest)
```bash
# Clone the repo
git clone https://github.com/Siddx6/petolife-launch.git

# Navigate into the folder
cd petolife-launch

# Open directly in your browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 2: Run with a Local Server (Recommended)
Using Python (comes pre-installed on most systems):
```bash
# Python 3
python3 -m http.server 8000

# Then open in browser
http://localhost:8000
```

Using Node.js:
```bash
npx serve .
# Then open: http://localhost:3000
```

That's it. No `npm install`. No `.env` files. No config.

---

### Vercel (Recommended for speed)
```bash
npx vercel
# Follow prompts — live URL in ~30 seconds
```

### Netlify
```bash
npx netlify-cli deploy --prod --dir .
```

---

## ✨ Features Built

| Feature | Description |
|---|---|
| 🆔 Animated Pet ID Card | Floating card with real data fields, barcode, and health stats |
| 📜 Scroll Reveal | Elements animate in as you scroll — `IntersectionObserver` API |
| 📊 Animated Counters | Stats count up with eased cubic interpolation on scroll |
| 🔔 Floating Event Pills | Live-like badges simulate real-time vet access events |
| 📱 Fully Responsive | Mobile-first layout, works on all screen sizes |
| 🎨 CSS Ring Animation | Pulsing concentric rings illustrating the identity concept |
| 🧭 Smart Nav | Shrinks on scroll, smooth anchor links throughout |

---

## 🧠 Technical Decisions

- **Single HTML file** — zero build tooling, instant setup, easy to deploy anywhere
- **No external JS libraries** — scroll reveal, counters, and animations are all vanilla JS
- **CSS custom properties** — consistent theming with `var(--forest)`, `var(--amber)`, etc.
- **`IntersectionObserver`** — performant scroll animations without scroll event listeners
- **Google Fonts only external dependency** — `Syne` (display) + `DM Sans` (body)
- **CSS animations over JS** — card float, ring pulse, and pill hover are pure CSS for 60fps performance

---

## 🤖 AI Tools Used

| Tool | Usage |
|---|---|
| **Claude (Anthropic)** | HTML/CSS code generation |
| **Prompt Engineering** | Iterative prompts for layout, animation, color palette, and copy |

Per challenge guidelines, AI usage is explicitly disclosed and encouraged. All code was reviewed, understood, and validated by the developer before submission.

---

## 📐 Design Assumptions

1. **Target users are two personas** — Pet Parents (emotional, trust-driven) and Vets (efficiency-driven). The page speaks to both.
2. **"Free forever" for individuals** is assumed as the go-to-market hook to drive adoption before monetising through vet clinic B2B plans.
3. **India-first framing** — stats and testimonials are India-specific to match PetOlife's market.
4. **Demo data** (Bruno the Golden Retriever, Dr. Mehta, etc.) is fictional and used purely for illustration.
5. **No backend required** for this launch page — it is a marketing/waitlist page, not the full product.

---

## 👤 Submitted By

**[Siddharth Kumar]**  
Full Stack Engineer — Summer Internship Applicant  
📧 siddharthkumar6669@email.com · 🔗 www.linkedin.com/in/siddharth-kumar-508333333 · 💻 github.com/Siddx6

---

*Submitted for PetOlife Code-A-Thon · May 2025*
