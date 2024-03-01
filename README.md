# BUHO
BUHO ANIMATION
body{
 /* margin: 0;
  padding: 0;
  box-sizing: border-box;*/
/*  background-color: no-repeat lineargradient(60deg,#B22222,#FFC0CB);*/
   background: linear-gradient(#B22222, #FFC0CB);
  background-size: cover;
}
.container 
{
  width: 400px;
  height: 600px;
  margin: 30px auto auto auto;
}
.body
{
  position: relative;
  left: 12%;
  top: 15%;
  bottom: 0;
  right: 0;
  width: 310px;
  height: 420px;
  background: #A52A2A;
  border-radius: 150px;
  
animation-name: color;
  animation-duration: 7s;
}

@keyframes color {
  from {background-color: #2CB0EA;}
  to {background-color: #193DCE;}
}

.ear
{
  position: absolute;
  background: #5CC1CB;
  top: -10px;
  width: 125px;
  height: 190px;
  background: #8B0000;
}
.ear:nth-child(1)
{
  border-radius: 100% 0% 100% 0%;
  transform: rotate(-50deg);
  left: 0;
  animation-name: orejascol;
  animation-duration: 7s;
}
.ear:nth-child(2)
{
  border-radius: 0% 100% 0% 0%;
  transform: rotate(50deg);
  right: 0;
  
  animation-name: orejascol;
  animation-duration: 7s;
}

@keyframes orejascol{
  from {background-color: #040DA4;}
  to {background-color: #181F92;}
}

.eyesContainer
{
  position: absolute;
  top: 45px;
  width: 180px;
  height: 180px;
  background:#D2691E;
  border-radius: 50%;
animation-name: bad;
  animation-duration: 7s;
}
.eyesContainer:nth-child(3)
{
  left: 0px;
}
.eyesContainer:nth-child(4)
{
  right: 0px;
}
.eyesContainer::before
{
  content: '';
  position: absolute;
  width: 125px;
  height: 125px;
  top: 20px;
  background: #fff;
  border-radius: 50%;
  z-index: 1;
}
.eyesContainer:nth-child(3)::before
{
  left: 15px;
}
.eyesContainer:nth-child(4)::before
{
  right: 15px;
}
.eyesContainer::after
{
  content: '';
  position: absolute;
  top: 40px;
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background: black;
  z-index: 2;
}
.eyesContainer:nth-child(3)::after
{
  left: 35px;
}
.eyesContainer:nth-child(4)::after
{
  right: 35px;
}
.pupil
{
  position: absolute;
  top: 70px;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #fff;
  z-index: 5;
}
.eyesContainer:nth-child(3) .pupil
{
  left: 50px;
}
.eyesContainer:nth-child(4) .pupil
{
  right: 80px;
}
.mouth
{
  position: absolute;
  top: 190px;
  left: 130px;
  width: 50px;
  height: 50px;
  background: #DAA520;
  clip-path: polygon(50% 100%, 0 0, 100% 0);
}
.belly
{
  position: absolute;
  top: 255px;
  right: 29px;
  border-radius: 50%;
  width: 253px;
  height: 166px;
  background:#D2691E;
  clip-path: circle(52.8% at 50% 54%);
  animation-name: bad;
  animation-duration: 7s;
}

@keyframes bad {
  from {background-color: #2CB0EA;}
  to {background-color: #EFF0D4 ;}
}

.pens
{
  position: absolute;
  top: 30px;
  width: 52px;
  height: 30px;
  border-radius: 50%;
  border-top: 2px solid transparent;
  border-bottom: 2px solid #4A3520;
}
.pens:nth-child(1)
{
  left: 60px;
}
.pens:nth-child(2)
{
  left: 140px;
}
.pens:nth-child(3)
{
  top: 60px;
  left: 25px;
}
.pens:nth-child(4)
{
  top: 60px;
  left: 100px;
}
.pens:nth-child(5)
{
  top: 60px;
  left: 180px;
}
.pens:nth-child(6)
{
  top: 90px;
  left: 60px;
}
.pens:nth-child(7)
{
  top: 90px;
  left: 140px;
}
.at {
  position: absolute;
  top: 220px;
  width: 100px;
  height: 120px;
  left: -45px;
  border-radius: 50% 50% 0px 0px;
  background: #4A3520;
  z-index: 5;
    

animation-name: b;
  animation-duration: 7s;
}

@keyframes b {
  from {background-color: #BF180B;}
  to {background-color: #93170D ;}
}

.at:nth-child(6)
{
  transform: rotate(15deg);
}
.at:nth-child(8)
{
  transform: rotate(-15deg);
  left: 255px;
}
.ats
{
  position: absolute;
  top: 119px;
  width: 35px;
  height: 60px;
  background: #4A3520;
  border-radius: 0% 0% 50% 50%;
animation-name: b;
  animation-duration: 7s;
}
.ats:nth-child(1)
{
  left: 32px;
}
.ats:nth-child(2)
{
  left: 65px;
}
.legs 
{
  position: absolute;
  top: 350px;
  width: 20px;
  height: 80px;
  background: #F99525;
  z-index: -1;
}
.legs:nth-child(9)
{
  left: 110px;
}
.legs:nth-child(10)
{
  right: 110px;
}
.hoof
{
  position: absolute;
  top: 80px;
  width: 8px;
  height: 18px;
  background: #F99525;
}
.hoof:nth-child(1)
{
  top: 77px;
  left: -5px;
  transform: rotate(50deg);
}
.hoof:nth-child(2)
{
  left: 6px;
}
.hoof:nth-child(3)
{
  top: 77px;
  left: 17px;
  transform: rotate(-50deg);
}

.esc{
  width: 200px;
  height: 200px;
  border-radius: 100%;
  background: #B0B0B0;
  position: relative;
  margin: auto;
  border: 30px solid #D81212;
  left: 85px;
  bottom: 100px;
animation-name: mover;
  animation-duration: 7s;
  animation-delay: 2s;
  animation-fill-mode: backwards;
}
@keyframes mover {
  0%   {background-color:#922B21 ; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:-200px;}
  75%  {background-color:#D35400; left:400px; top:-250px;}
  100% {background-color:#AED6F1; left:0px; top:0px;}
}
 


.esc2{
  width: 100px;
  height: 100px;
  border-radius: 100%;
  background: #2942AA;
  position: relative;
  margin: auto;
  border: 30px solid #D81212;
  left: 0px;
  bottom: -25px;
}
.triangulo {
     width: 0; 
     height: 0; 
     border-left: 50px solid #B0B0B0;
     border-top: 25px solid transparent;
     border-bottom:25px solid transparent; 
    
  position: absolute;
    height: 0;
    width: 0;
    top: 15px;
    left: 50px; 
  
    transform: rotate(-30deg)
}
.triangulo2 {
     width: 0; 
     height: 0; 
     border-left: 50px solid #B0B0B0;
     border-top: 25px solid transparent;
     border-bottom:25px solid transparent; 
  transform: rotate(-65deg);
  position: absolute;
    height: 0;
    width: 0;
    top: -50px;
    left: -65px; 
}
.triangulo3 {
     width: 0; 
     height: 0; 
     border-left: 55px solid #B0B0B0;
     border-top: 25px solid transparent;
     border-bottom:25px solid transparent; 
  transform: rotate(-85deg);
  position: absolute;
    height: 0;
    width: 0;
    top: -50px;
    left: -80px; 
}

h1 {
  text-align: center;
  animation: aparecerDesaparecer 4s infinite;
}
@keyframes aparecerDesaparecer {
        0% { opacity: 0; }
        50% { opacity: 1; }
        100% { opacity: 0; }
}
