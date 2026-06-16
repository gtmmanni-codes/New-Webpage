- {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'helvetica neue';
  }

html,
body {
height: 100%;
width: 100%;
}

h1{
display: inline-block;
max-width: 50%;
background-color: royalblue;
font-size: 40px;
color: white;

img {
height: 200px;
position: absolute;

    animation-name: dora;
    animation-duration: 2s;
    animation-delay: 1s;

    animation-fill-mode: forwards;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    animation-timing-function: linear;

}

img:hover{
animation-play-state: paused;
}

@keyframes dora {
from{
left: 0;
rotate: 0;
}
to{
rotate: 360deg;
left: 75%;
}
}
