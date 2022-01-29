# Javascript Animated Template
[Animate On Scroll Library](https://michalsnik.github.io/aos/)
![alt text][image]
## Assets
```javascript
<!-- AOS CSS -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
<!-- AOS.js -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({
      delay: 200, // values from 0 to 3000, with step 50ms
      duration: 1500, // values from 0 to 3000, with step 50ms
      once: false, // whether animation should happen only once - while scrolling down
      mirror: false, // whether elements should animate out while scrolling past them
    });
  </script>
```
[image]: https://github.com/yourwpmadesimple/javascript-animated-template/blob/master/AOS_Capture.png "AOS Capture"