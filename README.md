# konami.js
A simple Konami Code script that runs arbitrary code.
___
## About

You likely know the *Konami Code*, a sequence of buttons made famous for unlocking secrets in countless video games by the Japanese developer Konami.

To jog your memory:

# ↑↑↓↓←→←→BA
See? you've heard it before!

The code has arrived in the internet-hall-of-fame, existing on countless websites around the web. Now's your chance to join the rest of the world!
___
## How to use
1. Add konami.js to your HTML document.  
```
<script src="konami.js"></script>
```
2. In your main javascript file, add something along these lines:

```
let example = function () {
  /// Your code here ///
}
let konami = new Konami();
konami.activateFunction = example
konami.run()
```
3. You're done! input the konami code and watch your function activate! 
