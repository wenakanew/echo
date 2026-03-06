# **echo — Modern Audio Upload & Developer Dashboard UI**

**echo** is a beautifully-designed, fully-responsive HTML/CSS front-end built for audio-driven applications.
It includes a modern landing page, audio visualization card, upload interface, scrolling reviews section, authentication screens, and a full developer dashboard—all crafted with premium UI/UX principles, custom animations, and advanced CSS styling.

This project is ideal for:

* Audio processing tools
* AI voice/LLM audio applications
* SaaS product landing pages
* Developer dashboards & authentication flows
* File-upload utilities with modern UI

---

##  Features

###  Modern Aesthetic & Premium UI

* Soft gradients, floating shapes, glassmorphism elements
* Clean typography using the Inter font family
* Smooth micro-interactions and hover states
* Light, minimalist, Apple-like design language

###  Audio Visualization Card

* Animated waveform using CSS keyframe animations
* Live indicator with pulsing status dot
* Ambient rotating highlights for visual depth

###  Drag-and-Drop Upload Area

* Modern dashed-border drop-zone
* Hover effects & upload hints
* Fully responsive on all screen sizes

###  Hero Section

* Large typographic heading with gradient text
* Highlight accent underline effect
* Animated “online” pill indicator

###  Auto-Scrolling Review Carousel

* Infinite horizontal scrolling review feed
* Pause-on-hover
* Blurred glass cards with avatars & star ratings

###  Authentication System UI

Includes:

* Login / Signup tabbed UI
* Form fields with modern input styling
* Google sign-in button
* Password reset link
* Beautiful card layouts with shadows & smooth transitions

###  Developer Dashboard

* Sidebar navigation
* API key management UI
* Metrics dashboard (requests, usage, etc.)
* Code example blocks
* Plan badge
* Multiple content sections styled cleanly

---

##  Project Structure

```
/
├── index.html        # Main UI file containing all components
├── fonts/            # (optional) Custom font directory if added later
├── assets/           # (optional) Images, icons, SVGs
└── README.md         # Documentation file (this file)
```

Everything is contained in a single HTML document for easy modification and deployment.

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/echo.git
cd echo
```

### 2. Open the Project

Simply open **index.html** in any modern browser.

No build tools or frameworks are required.

---

##  Customization Guide

###  Colors & Gradients

All theme colors (backgrounds, accents, gradients) are located in the `<style>` block.
Search for:

```css
background: #1a1a1a;
background: radial-gradient(...);
background: linear-gradient(...);
```

###  Animations

Animations are defined using `@keyframes`:

* `pulse`
* `wave`
* `rotate`
* `float`
* `scrollReviews`

You can adjust durations and easing to match your brand.

###  Upload Area

Enhance functionality by attaching JavaScript event listeners:

```js
document.querySelector('.upload-area-modern')
  .addEventListener('click', () => {
      // open file picker or handle logic
  });
```

### Developer Dashboard

Insert dynamic data (usage, API keys, metrics) using JavaScript or API calls.

---

##  Responsive Design

The layout is fully responsive for:

* Desktop (full layout)
* Tablets
* Mobile (stacked sections)

Built using CSS grid, modern responsiveness techniques, and mobile-friendly spacing.

---

##  Components Overview

### 1. Navigation Bar

* Logo with underline aesthetic
* Smooth hover interactions on links
* Developer access button

### 2. Hero Section

* Large headline
* Audio card animation
* Product stats

### 3. Upload Section

* Modern drag-drop box
* Feature tags

### 4. Auto-Scrolling Reviews

* Glass cards
* Infinite animation

### 5. Login / Signup Screen

* Tabs for switching mode
* Clean form UI
* Google login button

### 6. Developer Dashboard

* API section
* Usage metrics
* Code examples
* Sidebar with active state

---

## 7. Browser Support

| Browser         | Supported |
| --------------- | --------- |
| Chrome          | ✅         |
| Edge            | ✅         |
| Safari          | ✅         |
| Firefox         | ✅         |
| Mobile Browsers | ✅         |

---

##  License

You may choose the license that matches your usage.
If unspecified, MIT License is recommended.

---

## ** Contributing**

Contributions, improvements, and feature expansions are welcome.

Send PRs or open issues with suggestions!

