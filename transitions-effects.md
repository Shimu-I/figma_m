# List of Transitions & Effects

# 🎬 List of Transitions & Effects (with Tools)

---

### 1. **Parallax Scrolling**

- **What it is:** Background moves slower than foreground → 3D illusion.
- **How it works:** Different layers scroll at different speeds.
- **Use it with:** ❌ Not in Figma → ✅ ProtoPie, Framer, GSAP (web).

---

### 2. **Fade In / Fade Out**

- **What it is:** Elements gradually appear/disappear.
- **How it works:** Opacity changes from 0 → 100% (or reverse).
- **Use it with:** ✅ Figma Smart Animate → ✅ Figmotion plugin → ✅ Any external tool.

---

### 3. **Slide / Translate Transition**

- **What it is:** Elements slide in/out from top, bottom, left, or right.
- **How it works:** X/Y position changes smoothly.
- **Use it with:** ✅ Native Figma transitions → ✅ Figmotion → ✅ ProtoPie / Framer.

---

### 4. **Scroll-triggered Animations**

- **What it is:** Animations happen only when scrolled into view.
- **How it works:** Triggered by scroll position (enter viewport).
- **Use it with:** ❌ Not in Figma → ✅ ProtoPie, Framer, GSAP.

---

### 5. **Sticky / Pinning Effects**

- **What it is:** An element stays fixed while content scrolls past.
- **How it works:** Object pinned until a new section replaces it.
- **Use it with:** ❌ Not in Figma → ✅ ProtoPie, Framer, Web code.

---

### 6. **Scroll Jacking (Snap Scroll)**

- **What it is:** Instead of free scrolling, screen snaps to sections.
- **How it works:** Scroll locked until animation completes, then jumps.
- **Use it with:** ❌ Not in Figma → ✅ ProtoPie, Framer, GSAP.

---

### 7. **Hover & Micro-interactions**

- **What it is:** Buttons glow, shake, bounce, expand on hover/click.
- **How it works:** Small animations on mouse-over or tap.
- **Use it with:** ✅ Native Figma (hover states) → ✅ Figmotion for extra flair → ✅ ProtoPie / Framer for advanced effects.

---

### 8. **Background Video / Motion**

- **What it is:** A video or motion background moves as you scroll.
- **How it works:** Looped video or animated Lottie.
- **Use it with:** ❌ Figma doesn’t support video → ✅ LottieFiles plugin for vector motion → ✅ ProtoPie / Framer / After Effects for real video.

---

### 9. **Split-screen Transitions**

- **What it is:** Page divides into two panels that move independently.
- **How it works:** Panels animate in opposite directions.
- **Use it with:** ✅ Figma Smart Animate (basic) → ✅ Figmotion (more control) → ✅ ProtoPie, Framer for scroll-driven versions.

---

### 10. **Page Load Transitions**

- **What it is:** Intro animations while content loads (logo spin, fade, etc.).
- **How it works:** Timer-based animation before showing content.
- **Use it with:** ❌ Figma doesn’t support “loading” states → ✅ Fake it with overlays + delay → ✅ ProtoPie, Framer, After Effects for real load animations.

---

### 11. **Magnetic / Cursor-follow Effects**

- **What it is:** Elements wobble or move slightly toward the cursor.
- **How it works:** Mouse position influences object position.
- **Use it with:** ❌ Not in Figma → ✅ ProtoPie (cursor tracking) → ✅ GSAP/Framer (web).

---

### 12. **3D / Flip Animations**

- **What it is:** Cards rotate or flip in 3D space.
- **How it works:** Rotation transform on X/Y/Z axis.
- **Use it with:** ❌ Not in Figma → ✅ After Effects, Framer, GSAP.

---

### 13. **Character / Mascot Animations (eye movement, waving, etc.)**

- **What it is:** A character illustration reacts (blinks, looks at cursor).
- **How it works:** Mouse position mapped to parts of the illustration.
- **Use it with:** ❌ Not in Figma → ✅ After Effects (character rig) → ✅ ProtoPie (cursor tracking).

---

### 14. **Drag / Swipe Transitions**

- **What it is:** Mobile-style swipeable screens/cards.
- **How it works:** Gesture input triggers animations.
- **Use it with:** ✅ Limited in Figma (click only, not drag) → ✅ ProtoPie, Principle, Framer for real drag.

---

### 15. **Looping Animations (Loaders, Spinners, Waves)**

- **What it is:** Repeated animations (infinite loop).
- **How it works:** Animated GIFs, Lottie, or timeline loop.
- **Use it with:** ❌ Not native in Figma → ✅ LottieFiles plugin → ✅ After Effects/Framer for looping.

---

# 📊 Quick Tool Guide

- **Figma Native:** Fade, slide, hover, overlays, Smart Animate, scroll frames.
- **Figma Plugins (Figmotion, LottieFiles):** Timeline keyframes, looping animations, vector motion.
- **External Tools (ProtoPie, Framer, After Effects, Principle):** Parallax, scroll-triggered, sticky/pinning, scroll jacking, cursor-follow, physics, 3D, background video.

# 🎬 Animation Types vs. Tools

| Animation Type | Figma Native | Plugins (Figmotion, LottieFiles) | External Tools (ProtoPie, Framer, After Effects, GSAP) |
| --- | --- | --- | --- |
| **1. Parallax Scrolling** | ❌ | ❌ | ✅ |
| **2. Fade In / Fade Out** | ✅ | ✅ | ✅ |
| **3. Slide / Translate** | ✅ | ✅ | ✅ |
| **4. Scroll-triggered Animations** | ❌ | ❌ | ✅ |
| **5. Sticky / Pinning Effects** | ❌ | ❌ | ✅ |
| **6. Scroll Jacking (snap scroll)** | ❌ | ❌ | ✅ |
| **7. Hover & Micro-interactions** | ✅ | ✅ | ✅ |
| **8. Background Video / Motion** | ❌ | ⚠️ Limited (Lottie vectors only) | ✅ |
| **9. Split-screen Transitions** | ✅ (basic Smart Animate) | ✅ | ✅ |
| **10. Page Load Transitions** | ❌ | ⚠️ Fake with overlays/timers | ✅ |
| **11. Magnetic / Cursor-follow Effects** | ❌ | ❌ | ✅ |
| **12. 3D / Flip Animations** | ❌ | ❌ | ✅ |
| **13. Character Animations (eyes, waving)** | ❌ | ⚠️ Limited (Lottie) | ✅ |
| **14. Drag / Swipe Transitions** | ⚠️ Click-only, no drag | ❌ | ✅ |
| **15. Looping Animations (spinners, loaders)** | ❌ | ✅ (Figmotion/Lottie) | ✅ |

---

### ✅ Legend:

- **✅ Supported fully**
- **⚠️ Limited / Workaround**
- **❌ Not possible**

---

## 🔑 Insights

- **Figma Native** → Good for **basic UI transitions** (fade, slide, hover, smart animate).
- **Plugins** → Extend Figma with **keyframes, looping, and Lottie vectors**, but still limited.
- **External Tools** → Needed for **scroll effects, cursor tracking, physics, 3D, video backgrounds, parallax**.
