# Tailwind CSS Setup

This project was created to learn how to install and configure Tailwind CSS using the Tailwind CLI.

## What I Learned

- Installing Tailwind CSS
- Initializing an npm project
- Understanding `package.json` and `package-lock.json`
- Using the Tailwind CLI
- Compiling CSS with the `--watch` flag
- Linking the generated `output.css` file to an HTML page
- Using basic Tailwind utility classes

## Technologies Used

- HTML5
- Tailwind CSS v4
- npm

## Installation

Clone the repository and navigate to this project.

```bash
npm install
```

## Run Tailwind

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

## Project Structure

```
08_Tailwand/
├── src/
│   ├── index.html
│   ├── input.css
│   └── output.css
├── package.json
├── package-lock.json
└── README.md
```

## Output

The page displays a simple message to verify that Tailwind CSS has been installed and configured successfully.

```
Hello, this is Manoj. Remember the name.

Tailwind CSS Working..
```

## Author

**Manoj Akula**