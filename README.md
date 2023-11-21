Index sources:

**Navigation Bar Customization**

The navigation bar for our website was constructed by taking inspiration from a tutorial found on YouTube by the channel Pure Code. The specific guidance was sourced from their video tutorial "How to Create a Responsive Navigation Bar," which can be accessed at https://www.youtube.com/watch?v=XM7sEpl0f7c. This tutorial provided a foundation upon which we built a customized and responsive navigation bar suitable for our website's design and functionality needs.

Additionally, the logo icon used within the navigation bar was sourced from RemixIcon, an open-source library that offers a variety of icons. The school icon used can be found on their website at https://remixicon.com/, which we integrated into our website's logo to enhance visual identification and branding.

Below is the HTML structure of our adapted navigation bar:

<!-- Navigation bar -->
<!-- Menu Icon/nav and logo Layout inspired by YouTube by Pure Code -->
<!-- Source: https://www.youtube.com/watch?v=XM7sEpl0f7c -->
<!-- Logo icon sourced from RemixIcon -->
<!-- Source: https://remixicon.com/ -->
<nav class="navbar">
  <div class="container">
    <a href="index.html" class="logo"><i class="ri-school-fill"></i><span>OSLOMET</span></a>
    <div class="search-box">
      <form action="">
        <input type="text" name="search" id="srch" placeholder="Search">
        <button type="submit"><i class="ri-search-line"></i></button>
      </form>
    </div>
    <div class="navigation">
      <input class="burger-toggle" type="checkbox" id="toggle-menu">
      <label for="toggle-menu" class="menu-icon"></label> <!-- Label to trigger the checkbox -->

      <ul class="menu">
        <li><a href="index.html">Home</a></li>
        <li><a href="canteen.html">Canteen</a></li>
        <li><a href="Library.html">Library</a></li>
        <li><a href="Accessibility.html">Accessibility</a></li>
        <li><a href="Topical.html">Topical</a></li>
      </ul>
    </div>
  </div> 
</nav>

The code has been customized to fit our website’s theme and interactivity. Adjustments made include the addition of a search box within the navigation bar and modifications to the menu for a more streamlined user experience.


**Web Slider Implementation**

For the image slider feature on our website, we utilized a pre-existing template as a base for our implementation. This template, "Slider and Slider CSS Nav Icon Layout," was originally designed by Hunter Garrett and is available on CodePen at the following URL: https://codepen.io/hunterbecton/pen/jOzVLGR.

Our adaptation involved modifying the image sources to align with our content and adjusting the CSS to match our site's design language. The original code provided a robust starting point, and with our modifications, it integrated seamlessly into the website. following block represents the adapted code which was included in our project:



<!-- Slider and Slider CSS Nav Icon Layout adapted from CodePen by Hunter Garrett -->
<!-- Source: https://codepen.io/hunterbecton/pen/jOzVLGR -->
<div class="slider-wrapper">
  <!-- Customized images for the slider -->
  <div class="slider">
    <img id="slide-1" src="/img/campus1.jpg" alt="Campus Image 1"/>
    <img id="slide-2" src="/img/campus2.jpg" alt="Campus Image 2"/>
    <img id="slide-3" src="/img/campus3.jpg" alt="Campus Image 3"/>
  </div>
  <!-- Navigation for the slider -->
  <div class="slider-nav">
    <a href="#slide-1">Slide 1</a>
    <a href="#slide-2">Slide 2</a>
    <a href="#slide-3">Slide 3</a>
  </div>
</div>

Our modifications ensured that the slider fits the visual and functional requirements of our website, providing users with an intuitive and aesthetically pleasing way to navigate through a series of images.

<!--Kilder som er brukt i kantine>

<!--https://youtube.com/-->
