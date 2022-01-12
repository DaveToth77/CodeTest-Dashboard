# CodeTest-Dashboard
#### Requirements

    TailwindCSS 3.0.13 with the following plugins;
    - autoprefixer 10.4.2
    - postcss-cli 9.1.0
    node
    npm

#### Installation

    run - npm install
    run - npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

#### Usage

    open index.html in browser for preview

#### Notes
To complete the code review I decided to use just HTML/CSS because functionality with a database was not required. I used TailwindCSS to style the page. I have recently done a project with it and wanted some additional practice. I felt it was a good compromise because it is a utility library so all components were done with HTML/CSS rather than imported.
I broke the project down into 4 elements completed in the following order:
1. Sidebar
   - I need to practice more on creating dynamic elements with strictly HTML/CSS. My experience with these type of functions is with React using states and Javascript functions.
   - because of that I coded a static sidebar in what would be the open position.
2. Navbar
   - The Navbar seems to be a good representation of the model.
3. Favorites section
   - Creating the cards to match the model was a fun challenge. The scroll function works but I could not find a way with HTML/CSS to make it scroll on the Arrow clicks.
   - the card menu is functional
4. Currently Live section
   - same as favorites section

Git was used to version control the project

I regret not using a framework based on the sidebar/content sliders and the inability to create components for reusable code. I did learn quite a bit even with this small exercise


