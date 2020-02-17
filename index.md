<style>
#imagelist a {
  width: 200px;
  height: 200px;
  position: relative;
  display: block;
}
#imagelist img {
  position: absolute;
  left: 0;
  top: 0;
  bottom: 100%;
  height: 100%;
  z-index: 1;
}
#imagelist img:hover {
  opacity: 0.2;
}
</style>

<div id="imagelist">
  <a href="">
    <img src="http://s0.geograph.org.uk/geophotos/03/97/06/3970600_94c29e78.jpg" />
    <p class="imgtext">This is the description text.
    </p>
  </a>
</div>

<img align="left" width="300" height="300" src="./assets/img/text-icon.svg" title="Image 1">
<img align="right" width="300" height="300" src="./assets/img/drawing-icon.svg" title="Image 2">
<img align="left" width="300" height="300" src="./assets/img/joke-icon.svg" title="Image 3">
<img align="right" width="300" height="300" src="./assets/img/image-icon.svg" title="Image 4">

