
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

. Need Node js and npm
. Install tailwind css.
    - `npm install tailwindcss @tailwindcss/cli`
. Make input css file. You can name anything
    - `@import "tailwindcss";`
. Run build command and generate output file
    - `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`
. Make HTML file and write code and link output.css.
. Check auto suggestion with tailwind extension
    - Tailwind CSS IntelliSense
. Interview Questions - output.css - contain all tailwind classes.

