# lite-alt-lightbox
alternative lightbox
<pre>
Compatibility with pages written for original Lightbox https://lokeshdhakar.com/projects/lightbox2/ .

Use:

in html>head
  &lt;link rel="stylesheet" href="../lb_style.css"&gt;
  
&lt;a href="../imgR/2.jpg" data-lightbox="imgR" data-title=""&gt;&lt;img src="../imgR/2-200.jpg"&gt;&lt;/a&gt;
&lt;a href="../imgR/3.jpg" data-lightbox="imgR" data-title=""&gt;&lt;img src="../imgR/3-200.jpg"&gt;&lt;a&gt;

in main.js type="module" :
  import { lb_init } from "./lb.js";
  
  if (document.querySelector('[data-lightbox]')) lb_init();
</pre>
