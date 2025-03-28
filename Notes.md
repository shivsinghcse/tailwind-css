
## What is Tailwind CSS?
- CSS Framework.
- Almost no need to write different CSS.
- A-lot of available classes for style.
- Every class has work for single utility.
- No need to override CSS.
- Fast development.
- Fast Performance.
- why fast??

## Better than other CSS frameworks?
- Its completely depends on your requirements.
- No framework is best until we do not know the requirements.
- But for performance and customisation, and saving time this is the one of the best framework.

## CDN
- CDN stands for Content Delivery Network

### Adding Tailwind CSS using CDN
```js 
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```
- For css usually we use `<link />` tag here we are using `<script></script>` because it is a javascript file. 
### Adding classes in html elements
```html
 <h1 class="text-3xl font-bold underline">Hello World!</h1>
 ```

### Extension for Tailwind CSS
- Tailwind CSS IntelliSense
- It does not work with CDN.


## What is the core principle behind Tailwind CSS?
- Utility First 

## Setup Tailwind CSS 4 with CLI

- Need Node js and npm
- Install tailwind css.
    - `npm install tailwindcss @tailwindcss/cli`
- Make input css file. You can name anything
    - `@import "tailwindcss";`
- Run build command and generate output file
    - `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`
- Make HTML file and write code and link output.css.
- Check auto suggestion with tailwind extension
    - Tailwind CSS IntelliSense
- Interview Questions - output.css - contain all tailwind classes.

### 1 rem = 16px

### How to apply any style on all child -> [&>*]:class

```html
<header class="bg-black text-white">
        <nav>
            <ul class="list-none flex [&>*]:flex">
                <li><a href="#" class="p-3 hover:bg-zinc-900">Home</a></li>
                <li><a href="#" class="p-3 hover:bg-zinc-900">News</a></li>
                <li><a href="#" class="p-3 hover:bg-zinc-900">Contact</a></li>
                <li><a href="#" class="p-3 hover:bg-zinc-900">About</a></li>
            </ul>
        </nav>
    </header>
```

## Working with Colors in Tailwind


- How many colors tailwind support by default
    - red, orange, amber, yellow, lime, green, emerald, teal, cyan, sky, blue, indigo, violet, purple, fuchsia, pink, rose, slate, gray, zinc, neutral, stone.

- The entire color palette is available across all color related utilities, including things like background color, border color, fill, caret color, and many more.

- Colors shades range
    - lightest(50), 100, 200, 300, 400, 500, 600, 700, 800, 900 darkest(950)
    - Every color in the default palette includes 11 steps, with 50 being the lightest, and 950 being the darkest.

- Interview questions

    - Which colors do not have shades in tailwind
        - black and white color do not have shades in tailwind
    - how to apply color to underline in css

- Utility	Description
    - bg-* Sets the background color of an element
    - text-*	Sets the text color of an element
    - decoration-*	Sets the text decoration color of an element
    - border-*	Sets the border color of an element
    - outline-*	Sets the outline color of an element
    - shadow-*	Sets the color of box shadows
    - inset-shadow-*	Sets the color of inset box shadows
    - ring-*	Sets the color of ring shadows
    - inset-ring-*	Sets the color of inset ring shadows
    - accent-*	Sets the accent color of form controls
    - caret-*	Sets the caret color in form controls
    - fill-*	Sets the fill color of SVG elements
    - stroke-*	Sets the stroke color of SVG elements
    
- go to tailwindcss website color page read more about it...    