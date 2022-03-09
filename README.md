# Multicolor Text

- CSS & HTML
- 100% Personalizable

<h2 align="center"> 💻 Código  </h2>

### HTML

```html
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<div class="wrapper">

<div class="neon-wrapper">
	<span class="txt">Panda.xyz</span>
	<span class="gradient"></span>
	<span class="dodge"></span>
</div>
	
</div>
</body>
</html>
<style> .wrapper{
	height:800px;
	display:flex;
	align-items: center;
	justify-content: center;
	background:#000000;
}

.txt{
	color:#ffffff;
	background:#000000;

	font-family: Arial;
	font-weight: bold;
	font-size: 200px; 
	text-transform: uppercase;
}

.txt::before{
	content:'Panda.xyz';
	position:absolute;
	mix-blend-mode: difference;
	filter:blur(2px);
}
.neon-wrapper{
	display:inline-flex;
	overflow:hidden;
	filter:brightness(200%);
}

.gradient {
	position:absolute;
	mix-blend-mode: multiply;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:linear-gradient(114.23828586504828deg, rgba(128, 234, 209,1) 6.980769230769232%,rgba(91, 52, 162,1) 93.90384615384615%);
}

.dodge {
    background: radial-gradient(circle,white,black 35%) center / 25% 25%;
    position: absolute;
    top:-100%;
    left:-100%;
    right:0;
    bottom:0;
  

    mix-blend-mode: color-dodge;
    animation: dodge-area 3s linear infinite;
}

@keyframes dodge-area{
	to{
		transform: translate(50%,50%);
	}
}

 </style>
```

### CSS

<div> </div>

```css
<style> .wrapper{
	height:800px;
	display:flex;
	align-items: center;
	justify-content: center;
	background:#000000;
}

.txt{
	color:#ffffff;
	background:#000000;

	font-family: Arial;
	font-weight: bold;
	font-size: 200px; 
	text-transform: uppercase;
}

.txt::before{
	content:'Panda.xyz';
	position:absolute;
	mix-blend-mode: difference;
	filter:blur(2px);
}
.neon-wrapper{
	display:inline-flex;
	overflow:hidden;
	filter:brightness(200%);
}

.gradient {
	position:absolute;
	mix-blend-mode: multiply;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:linear-gradient(114.23828586504828deg, rgba(128, 234, 209,1) 6.980769230769232%,rgba(91, 52, 162,1) 93.90384615384615%);
}

.dodge {
    background: radial-gradient(circle,white,black 35%) center / 25% 25%;
    position: absolute;
    top:-100%;
    left:-100%;
    right:0;
    bottom:0;
  

    mix-blend-mode: color-dodge;
    animation: dodge-area 3s linear infinite;
}

@keyframes dodge-area{
	to{
		transform: translate(50%,50%);
	}
}
```
