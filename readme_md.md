# 🧩 Interactive Venn Diagram Practice: Set Theory Expression Match

A responsive, client-side web application designed to help students master set theory operations (Union, Intersection, Complement, Difference). Students observe a dynamically generated, pre-shaded Venn diagram and must identify the correct algebraic expression that produces the shading.

Built with an emphasis on **Growth Mindset** and **Productive Struggle**, this tool doesn't just tell students when they are wrong; it provides targeted visual clues and conceptual definitions to help them arrive at the correct answer on their own.

## ✨ Features

*   **Dynamic SVG Shading:** Uses advanced SVG masking and clipping paths to accurately render complex set intersections without pixelation.
*   **MathJax Integration:** Beautifully renders LaTeX set theory notation (e.g., \\( (A \cup B)^c \cap C \\)) that automatically scales to fit any screen size.
*   **Three Difficulty Tiers:**
    *   *Easy:* Single operations and basic complements.
    *   *Medium:* Two-step operations and parentheses.
    *   *Advanced:* Complex three-set logic requiring careful deduction.
*   **Productive Struggle Feedback:** When a student selects an incorrect expression, the app evaluates what their chosen expression *would* have shaded, compares it to the actual diagram, and provides specific hints (e.g., *"The expression you chose includes the region exclusively inside A, but notice that this region is blank in the diagram."*).
*   **Gamification:** Tracks current correct-answer streaks to encourage continuous practice.
*   **Fully Responsive:** Built with Tailwind CSS, ensuring a seamless experience across desktop, tablet, and mobile devices.

## 🛠️ Technologies Used

This project is entirely front-end and requires no build steps or bundlers.

*   **HTML5 / SVG:** For structure and dynamic graphics rendering.
*   **Vanilla JavaScript (ES6+):** For state management, math evaluation, and DOM manipulation.
*   **[Tailwind CSS](https://tailwindcss.com/):** (via CDN) For rapid, modern UI styling.
*   **[MathJax 3](https://www.mathjax.org/):** (via CDN) For rendering algebraic notation.

## 🚀 Getting Started

Because this is a zero-dependency project, running it locally is incredibly simple.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/venn-diagram-practice.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd venn-diagram-practice
    ```
3.  **Run the application:**
    Simply open the `index.html` file in any modern web browser.
    *   *Alternatively, if using VS Code, you can use the "Live Server" extension.*

## 🧠 Educational Pedagogy

This tool was designed with modern math education philosophies in mind:
*   **Visual Pattern Recognition:** By removing numbers from the diagram and presenting a pre-shaded image first, students are forced to think conceptually about boundaries and intersections rather than relying on memorized region numbers.
*   **Growth Mindset Affirmations:** Incorrect answers are met with randomized, encouraging affirmations to reduce math anxiety.
*   **Scaffolded Hints:** Instead of revealing the correct answer upon failure, the app provides definitions for the symbols the student chose and compares their logical outcome to the visual prompt, keeping the cognitive load on the student.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
If you have ideas for new complex mathematical expressions to add to the `QUESTION_BANK` or improvements to the SVG masking logic, feel free to fork the repository and submit a Pull Request.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).