<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.rawgit.com/jeromeetienne/AR.js/2.0.8/aframe/build/aframe-ar.js"></script>
  </head>
  <body>
    <a-scene embedded arjs>
      <!-- Kamera AR -->
      <a-entity camera position="0 0 0"></a-entity>

      <!-- Objek 1: Kotak -->
      <a-box position="-2 1 -5" color="red" scale="0.5 0.5 0.5"></a-box>

      <!-- Objek 2: Silinder -->
      <a-cylinder position="2 1 -5" radius="1" height="2" color="blue" scale="0.5 0.5 0.5"></a-cylinder>

      <!-- Objek 3: Sphere -->
      <a-sphere position="0 1 -5" radius="1.5" color="green" scale="0.5 0.5 0.5"></a-sphere>

      <!-- Objek 4: Tetrahedron -->
      <a-tetrahedron position="-4 1 -5" radius="1" color="yellow" scale="0.5 0.5 0.5"></a-tetrahedron>

      <!-- Objek 5: Dodecahedron -->
      <a-dodecahedron position="4 1 -5" radius="1" color="purple" scale="0.5 0.5 0.5"></a-dodecahedron>

      <!-- Deteksi Pola dengan "hiro" -->
      <a-marker preset="hiro"></a-marker>
    </a-scene>
  </body>
</html>
