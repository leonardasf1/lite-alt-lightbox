# lite-alt-lightbox
alternative lightbox

Compatibility with pages written for original Lightbox https://lokeshdhakar.com/projects/lightbox2/ .

Use:

in html>head
  <link rel="stylesheet" href="../lb_style.css">
  
<a href="../imgR/3.jpg" data-lightbox="imgR" data-title=""><img src="../imgR/3-200.jpg"></a>

in main.js type="module" :
  import { lb_init } from "./lb.js";
  
  if (document.querySelector('[data-lightbox]')) lb_init();
