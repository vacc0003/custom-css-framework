# 🪶 TailFeather CSS

TailFeather CSS is a lightweight, customizable utility-first CSS framework inspired by Tailwind. Built with Sass, it offers a simplified set of utility classes and base styles for rapid development.

---

## 📦 Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/vacc0003/custom-css-framework.git
    cd custom-css-framework
    git checkout main
    ```

2. **Install Sass**

    If you don’t already have Sass installed, install it globally using npm:

    ```bash
    npm install -g sass
    ```

3. **Start the Sass watcher**

    Compile the Sass files into CSS using the following command:

    ```bash
    sass --watch src/main.scss:css/style.css
    ```

    This will watch for changes in your Sass files and automatically update `css/style.css`.

---

## 🚀 Usage

1. **Include the compiled CSS file in your HTML**

    ```html
    <link rel="stylesheet" href="css/style.css">
    ```

2. **Use TailFeather utility classes in your markup**

    ```html
    <div class="p-4 bg-primary text-primary rounded-lg">
      Welcome to TailFeather CSS!
    </div>
    ```

3. **Customize the framework**

    You can extend or override the styles by editing the SCSS files in:

    - `src/base/`
    - `src/components/`
    - `src/utilities/`

    Make changes and re-run the `sass --watch` command to compile updated styles.

---

## 🧰 Features

- Utility-first class naming
- Built with SCSS for easy customization
- Lightweight and fast to compile
- Inspired by Tailwind but simplified

---
