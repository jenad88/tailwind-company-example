# tailwind-company-example
Tailwind example project learned from Dr Sahand Ghavidel's course - Tesla clone

npm install -D tailwindcss
npx tailwindcss init

tailwind.config.js:
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

src/input.css:
@tailwind base;
@tailwind components;
@tailwind utilities;

npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch