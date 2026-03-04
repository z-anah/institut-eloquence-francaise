# ThumbTap Learning

**Goal**  
Mobile learning with one thumb. One action. No thinking.

---

**Target**
- Mobile only
- Portrait
- Bottom-screen interaction
- Single-thumb use

---

**Flow**
Lessons → Exercises → Player → Exercises

---

**Exercise Behavior**
- First tap: play TTS (en-US)
- Second tap: next item
- End of list: return to Exercise Selector

---

**UI Rules**
- Dark mode only
- Large text
- Large tap zones
- Bottom half of screen
- One main action per screen

---

**Images**
- One image per item
- Image displayed as card background
- Text over image with contrast overlay
- No `<img>` inside cards

---

**Audio**
- Web Speech API
- User-triggered only
- Cancel previous audio before playing new

---

**Data System**
- All content in `data.js`
- Items contain `{ text, img }`
- Data only, no logic
- Exercises reuse the same data

---

**Code Rules**
- HTML + Vue CDN + Tailwind CDN
- One page = one file
- No router, no build tools
- Reuse logic, change data only

---

**Golden Rule**
If it cannot be used with one thumb without explanation, do not add it.