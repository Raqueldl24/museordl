# museordl
>>>>>perspective
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
     <script src="https://supereggbert.github.io/aframe-htmlembed-component/dist/build.js"></script>

        </head>
  <body>
    <a-scene>
      <a-assets>
        <img id="suelo" src="suelos.jpg">
        <img id="pared" src="paredes.jpg">
       
      </a-assets>
   
    
     <a-entity> 
    
      <a-box position="0 0 -5.5" rotation="0 0 0" width="5" height="2.5" depth="0.1" src="#pared"></a-box>
      <a-box position="0 -1 -4.5" rotation="-90 0 0" width="5" height="3" depth="0.1" src="#suelo"></a-box>
      <a-box position="-1 0 -4.5" rotation="0 90 0" width="3" height="2.5" depth="0.1" src="#pared"></a-box>
      <a-box position="1 0 -4.5" rotation="0 90 0" width="3" height="2.5" depth="0.1" src="#pared"></a-box>
      <a-box position="0 1 -4.5" rotation="-90 0 0" width="3" height="2.5" depth="0.1" src="#pared"></a-box>
    </a-entity> 
     <a-sky color="#ECECEC"></a-sky> 
    </a-scene>
  </body>
  </html>
      =======
