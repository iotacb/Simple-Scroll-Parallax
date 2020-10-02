# Simple-Scroll-Parallax

A simple script to create simple parallax scrolling effects.

## Installation

With NPM
```bash
npm i simple-scroll-parallax.js
```

Without NPM
```bash
<script src="https://cdn.jsdelivr.net/npm/simple-scroll-parallax.js@1.0.0/src/simple-scroll-parallax.min.js"></script>
```

## Usage

First you have to initialize the script.

```html
    <script>
        SimpleParallax();
    </script>
```

Then just add the 'sp-target' attribute to the element that should get an parallax scrolling effect.

```html
<body>
    <section>
        <h1 sp-target>This is simple-scroll-parallax!</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, obcaecati.</p>
    </section>
</body>
```

## Advanced

When initializing the script, you can pass some parameters with it to change the default behavior of the script.
```html
    <script>
        SimpleParallax({
            targetSelector: "sp-target", // Change the target attribute
            transition: "transform .3s ease-in-out", // Change the transition of the targeted elements
            speed: .6, // Change the speed (strength) of the parallax effect
            bounce: 10 // Set a delay between each update to increase performance
        });
    </script>
```

## License
[MIT](https://github.com/iotacb/Simple-Scroll-Parallax/blob/main/LICENSE)
