.heart {
  fill: red;              /* Only works for SVG elements */
  position: relative;
  top: 5px;
  width: 50px;
  animation: pulse 1s ease infinite;
}
#heart {
  position: relative;
  width: 100px;
  height: 90px;
  text-align: center;
  font-size: 16px;
  animation: pulse 1s ease infinite;  /* Add animation here too */
}
@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.3); }
  100% { transform: scale(1); }
}
