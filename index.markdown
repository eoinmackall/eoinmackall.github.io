---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div id="container" style="width:100%">                                   
  <div id="left" style="float:left; width:40%;"> 
  <h2><b>Eoin Mackall</b></h2>

  <p>I like to think about algebraic geometry and intersection theory but, I have a lot of mathematical interests outside of these areas.</p>

  <p>I’m currently a Visiting Assitant Professor at the University of California, Santa Cruz.</p>
  </div>                     
  
  <div id="right" style="float:right; width:58%;">
    <img id="randomImage" src="" alt="Random Image">
    <script> 
      const images = [
      "/files/images/home_1.png",
      "/files/images/home_2.png",
      "/files/images/home_3.png",
      ];
      const randomIndex = Math.floor(Math.random() * images.length);
      const randomImage = images[randomIndex];
      const imageElement = document.getElementById("randomImage");
      imageElement.src = randomImage;
    </script>
  </div>                   
</div>
