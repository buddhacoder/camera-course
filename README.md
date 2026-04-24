# The Camera Course

A complete interactive course on photography and videography for YouTube — built around the Sony ZV-E10.

## 📖 Live Site

Once GitHub Pages is enabled, this site will be at:
**https://buddhacoder.github.io/camera-course/**

## 🧭 What's Inside

- **Lesson I: Exposure Fundamentals** — aperture, shutter, ISO, focal length. Every concept gets a slider you can drag.
- **Lesson II: Color & Look** — white balance, picture profiles, zebras. Making footage look intentional.
- **Lesson III: Camera Setup** — a 16-step walkthrough that configures your ZV-E10 for YouTube, with auto-saving progress.
- **Lesson IV: Audio Fundamentals** — levels, mic distance, mic types. The cheapest upgrade with the biggest impact.
- **Lesson V: Lighting Fundamentals** — hard vs soft, 3-point lighting, the free key light in every window.
- **Lesson VI: Composition & Framing** — shot sizes, rule of thirds, headroom.
- **Lesson VII: Camera Movement** — pan, tilt, push, pull, and the anti-zoom rule.

## 🔧 How It's Built

Single-file HTML with React + Tailwind loaded from CDN. No build step. Just serve `index.html` and you're done.

## 🎨 Customizing

Open `index.html` in any editor. Everything is in one file:
- Color tokens are in the `c` object near the top of the script tag
- Each lesson is its own React component
- Hash routing (`#/optics`, `#/color`, `#/setup`) means you can deep-link

## 📜 License

Personal use.
