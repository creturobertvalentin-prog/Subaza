# Will You Be My Valentine? ❤️

A fun and interactive webpage that asks the girl to be your Valentine.

## Features ✨

- **Animated Button Responses**: Clicking "No" causes the "Yes" button to grow and the "No" button to move randomly.
- **Modal Popup**: Clicking "Yes" or repeatedly clicking "No" triggers a popup with a cute message.
- **Embedded GIF**: Displays a transparent animated GIF using `mix-blend-mode`.
- **Fully Responsive**: Adjusts layout based on screen size.

## How It Works ⚙️

### HTML Structure 🏗️

- A `<h1>` element asks, "Will you be my Valentine?"
- Two `<button>` elements ("Yes" and "No") inside a `.button-container`.
- A modal (`.modal`) and overlay (`.modal-overlay`) for displaying popups.
- A `.gif-container` contains an `<img>` element for the GIF.

### CSS Magic 🎨

- **Flexbox Layout**: Centers content using `display: flex`.
- **Button Styling**: `transition` and `transform` effects on hover.
- **Modal Popup**: Hidden by default, appears when `display` is changed to `block`.
- **GIF Transparency**: `mix-blend-mode: multiply;` blends the GIF with the background.

### JavaScript Interactions ⚡

#### `noButton` Behavior

1. Click increases `noCount`.
2. If clicked **5 times**, a modal pops up with a message.
3. The "Yes" button **increases in size** and the "No" button **moves randomly** on the screen.

#### `yesButton` Behavior

- Clicking "Yes" **immediately** triggers a modal popup with a love message.

#### `openModal(message)`

- Updates modal text and makes it visible along with the overlay.

#### `closeModal()`

- Hides the modal and overlay when clicking the "Close" button.

## How to Run 🚀

1. Download the files or clone this repository.
2. Open `index.html` in any modern browser.
3. Have fun! 🎉


## Technologies Used 🖥️

- **HTML** - Structure of the page.
- **CSS** - Styling and animations.
- **JavaScript** - Handles interactive elements.

---

Enjoy the Valentine fun! 💖

 ## Preview
 [![Demo](https://img.youtube.com/vi/ctPFp4Ppdgc/0.jpg)](https://www.youtube.com/watch?v=ctPFp4Ppdgc)

