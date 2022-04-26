# Wails + React Typescript

## About

This is a Wails template project with React and TypeScript, using Vite for
asset bundling. It comes with the bare minimum, and can be extended by following
the guides in this README. 

To create a project using this template run:
`wails init -n [Your Appname] -t https://github.com/lontten/wails-vite-react-ts`

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend`
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this in your
browser and connect to your application.




## Building

To build a redistributable, production mode package, use `wails build`.

## Known Issues

- When making changes to the frontend, the browser reload will often happen too fast, causes issues. A refresh will fix the page.
- Typechecking is turned off due to Wails depending on the frontend to build before it will compile the backend and generate bindings.
- If you find any other problems, please create an issue.

