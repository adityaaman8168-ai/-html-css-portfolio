# -html-css-portfolio
A responsive personal portfolio website built using HTML, CSS, and JavaScript.
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#111827;
color:white;
}

nav{
display:flex;
justify-content:space-between;
padding:20px 10%;
background:#1f2937;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav a{
color:white;
text-decoration:none;
}

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero h1{
font-size:50px;
}

.btn{
background:#2563eb;
padding:12px 25px;
margin-top:20px;
color:white;
text-decoration:none;
border-radius:6px;
}

section{
padding:60px 10%;
}

.cards{
display:flex;
gap:20px;
flex-wrap:wrap;
margin-top:20px;
}

.card,.project{
background:#1f2937;
padding:20px;
border-radius:10px;
width:250px;
}

form{
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:12px;
border:none;
border-radius:5px;
}

button{
padding:12px;
background:#2563eb;
border:none;
color:white;
cursor:pointer;
}

footer{
text-align:center;
padding:20px;
background:#1f2937;
margin-top:50px;
}