```markdown
# Pink Envelope Interactive Animation

Source : https://github.com/heryyy/pink-envelope

A simple, lightweight HTML/CSS/JavaScript demo of a floating pink envelope that “opens” to reveal a cute handwritten message, with animated hearts and sparkles. Clicking the envelope (or the Open/Close buttons) toggles the envelope flap and letter animation.

---

## 🔍 Project Structure

```

.
├── index.html      ← Main HTML file
└── README.md       ← This documentation

````

All styles and scripts are inlined in `index.html` for ease of use. No build tools or server required.

---

## ✨ Features

- **Floating Envelope**  
  The entire envelope gently floats up and down (`@keyframes float`).

- **Open/Close Interaction**  
  - Click envelope or “Open Envelope” button to open the flap and slide the letter out.  
  - Click “Close Envelope” button to reset.

- **Animated Hearts & Sparkles**  
  When open, hearts rise up with side-to-side sway and sparkles twinkle and float.

- **Customizable Colors & Fonts**  
  CSS variables let you adjust envelope, flap, heart, sparkle, wax seal, and background colors.  
  Includes a handwritten cursive font (Handlee) for the message.

---

## 🚀 Usage

1. **Download or Clone**  
   ```bash
   git clone https://github.com/your-username/pink-envelope-demo.git
   cd pink-envelope-demo
````

2. **Open in Browser**
   Simply open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).

3. **Interact**

   * Click the envelope graphic, or
   * Click the **Open Envelope** / **Close Envelope** buttons.

---

## 🔧 Customization

* **Message Text**
  Edit the two `<p>` tags inside `.message`:

  ```html
  <div class="message">
    <p>Your first line here,</p>
    <p>Your second line here</p>
  </div>
  ```

* **Colors**
  Change CSS variables at the top of the `<style>` block:

  ```css
  :root {
    --color-env:    #FFB7C5;  /* envelope pocket */
    --color-env2:   #ff9aad;  /* pocket bottom */
    --color-flap:   #ff8da1;  /* envelope flap */
    --color-bg:     #ed7fca;  /* page background */
    --color-heart:  #ff85a2;  /* heart shapes */
    --color-sparkle:#fff;     /* sparkles */
    --wax-red:      #c04040;  /* wax seal (reserved) */
  }
  ```

* **Font**
  The handwritten look is provided by Google Fonts “Handlee”. To change, swap the `<link>` in `<head>` and update `.message`’s `font-family`.

* **Animation Timing & Behavior**
  Tweak the various `@keyframes` durations and easing functions to your liking.

---

## 🛠️ Dependencies

* [jQuery 3.6.0](https://code.jquery.com/jquery-3.6.0.min.js) for simple DOM toggling.
  (Can be replaced with vanilla JS if desired.)

---

## 🤝 Contributing

Feel free to open issues or submit pull requests for:

* Additional envelope effects (wax seal stamping, confetti bursts, etc.)
* Accessibility enhancements
* Vanilla-JS refactor (no external libs)
* Performance optimizations

---

```
```
