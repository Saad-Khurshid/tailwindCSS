# TailwindCSS for simple html5/CSS3 project

This project demonstrates a fully responsive (mobile first) design using TailwindCSS

## Project Setup

1.  ### Dev dependencies

    > yarn add -D tailwindcss postcss autoprefixer vite

2.  ### Init tailwindCSS with postCSS

    > npx init tailwindcss -p
    > Here, -p flag indicates to use postcss

3.  ### Run the project
    > vite

## Tailwind break points for screen sizes

Break points are min-width media queries. \
Styling affects selected break point and onwards.

```
{
   "sm": "640px",
   "md" : "768px",
   "lg": "1024px",
   "xl": "1280px",
   "2xl": "1536px"
}
```
