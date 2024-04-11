## Tailwind CSS Build Process

This section details how to build your Tailwind CSS styles using the command-line interface (CLI).

**Start the build process:**

Run the following command in your terminal to scan your template files for Tailwind classes and generate the output CSS file:

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
