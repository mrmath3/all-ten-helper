# All Ten Helper

Solver for [Beast Academy's **All Ten** daily challenge](https://beastacademy.com/all-ten).  
Enter the four digits for the day and instantly see all valid expressions that make each number 1–10.

---

<p align="center">
  <a href="https://mrmath3.github.io/all-ten-helper/">
    <img src="https://img.shields.io/badge/Open%20Solver-Click%20Here-blue?style=for-the-badge" alt="Open Solver">
  </a>
</p>

---

## About

The All Ten puzzle gives you four digits each day. The challenge is to combine them with `+ – × ÷`, parentheses, and concatenation (e.g. turning 1 and 2 into 12) to make every integer from 1 to 10.

This helper runs entirely in your browser. It:
- Lists **all expressions** found for each target number 1–10
- Deduplicates equivalent expressions
- Works offline once loaded
- Supports loading digits directly from the URL (see below)

---

## Usage

1. Visit the [solver](https://mrmath3.github.io/all-ten-helper/).
2. Enter today’s four digits (e.g. `1,2,2,8`) and click **Solve**.
3. Browse the solutions for each target.

### Quick tips
- Use the button at the top to open Beast Academy’s puzzle in a new tab.
- You can also pass digits directly in the URL, e.g.:

  ```
  https://mrmath3.github.io/all-ten-helper/#1,2,2,8
  ```

  or

  ```
  https://mrmath3.github.io/all-ten-helper/?nums=1,2,2,8
  ```

---

## Development

This project is a single self-contained `index.html` file.  
All logic is written in vanilla JavaScript (ported from the original Python solver).

To run locally:
```bash
git clone https://github.com/mrmath3/all-ten-helper.git
cd all-ten-helper
open index.html   # or double-click the file
```

---

## License

[MIT License](LICENSE)

---

## Acknowledgments

- Inspired by [Beast Academy](https://beastacademy.com/all-ten).
- Solver logic based on the original Python code for enumerating expressions.
