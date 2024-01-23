# prachproColab

.our-team .picture::before {
content: "";
width: 100%;
height: 0;
border-radius: 50%;
background-color: #0d1b48;
position: absolute;
bottom: 135%;
right: 0;
left: 0;
opacity: 0.9;
transform: scale(3);
transition: all 0.3s linear 0s;
}

.our-team:hover .picture::before {
height: 100%;
}

.our-team .picture::after {
content: "";
width: 100%;
height: 100%;
border-radius: 50%;
background-color: #0d1b48;
position: absolute;
top: 0;
left: 0;
z-index: -1;
}

.our-team {
padding: 30px 0 40px;
margin-bottom: 30px;
background-color: #ffffff;
text-align: center;
overflow: hidden;
position: relative;
}
