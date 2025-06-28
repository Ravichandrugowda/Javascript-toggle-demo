# Is JavaScript Easy? – Interactive Demo

A minimal web page that lets visitors interactively answer the age‑old question **“Is JavaScript easy?”** with two buttons, and immediately see the heading text change based on their choice.

## Demo

Add a screenshot named `screenshot.png` here once you have one, and if you deploy to GitHub Pages link it below:

```
![Screenshot of the demo](screenshot.png)
```

Live demo (GitHub Pages): [https://your-username.github.io/is-javascript-easy-demo/](https://your-username.github.io/is-javascript-easy-demo/)

---

## Features

* **Pure HTML, CSS & vanilla JavaScript** – zero build tools or frameworks
* Two call‑to‑action buttons ("Yes" / "No") that update the heading in real time
* Simple, readable code that’s perfect for absolute beginners
* Fully responsive layout thanks to percentage widths

## File structure

```text
.
├── index.html   # main webpage (HTML, CSS, JS in one file)
└── README.md    # project documentation (you’re reading it!)
```

## Getting started

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/is-javascript-easy-demo.git
   cd is-javascript-easy-demo
   ```
2. **Run locally** – simply open `index.html` in your favourite browser.

   ```bash
   start index.html   # Windows
   # or
   open index.html    # macOS
   # or
   xdg-open index.html  # Linux
   ```

There’s no build step or package install – just open and go.

## How it works

The magic happens in **six lines** of JavaScript at the bottom of `index.html`:

```js
// Change heading to the positive message
document.getElementById("B1").onclick = function() {
  document.getElementById("Heading").innerHTML = "Yes, JavaScript is easy guys";
};

// Change heading to the encouragement message
document.getElementById("B2").onclick = function() {
  document.getElementById("Heading").innerHTML = "No – but practise makes perfect!";
};
```

Each button finds the heading by its ID `Heading` and swaps the text content. That’s it!

## Customising the demo

* **Colours & fonts** – tweak the CSS inside `<style>`.
* **Messages** – edit the strings in the JavaScript functions.
* **Layout** – replace the inline styles with your own stylesheet if you prefer.

## Contributing

Pull requests are welcome. If you spot a typo, bug, or have a suggestion:

1. Open an issue to discuss it
2. Fork the repo
3. Create a feature branch
4. Commit your changes
5. Open a PR

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

