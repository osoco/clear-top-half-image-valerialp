JS

clearTopHalf(picture){
  picture.classList.add('under');
}


CSS
.container{
  position: relative;
}
.whiteBlock{
  width: 200px;
  height: 170px;
  position: absolute;
  z-index: 1;
}
.under{
  z-index: 2;
}


// En esta solución se trata de sobreponer un bloque blanco sobre la parte superior de la imagen
