.gif {
    position: absolute;
}

/*NAV CODE*/
.modalDialog {
	position: fixed;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: rgba(0,0,0,0.8);
	z-index: 99999;
	opacity:0;
	-webkit-transition: opacity 10ms ease-in;
	-moz-transition: opacity 10ms ease-in;
	transition: opacity 10ms ease-in;
	pointer-events: none;
}

.modalDialog:target {
	opacity:1;
	pointer-events: auto;
}

.modalDialog > div {
	width: 400px;
	position: relative;
	margin: 10% auto;
	padding: 5px 20px 13px 20px;
	border-radius: 10px;
	background-image: url(menu.png);
    background-size:contain;
    background-repeat: no-repeat;
	
}

.nav {
    position: absolute;
    font-family: eight-bit madness;
    font-size: 60px;
    top: 680px;
    left: 710px;
    z-index: 300;
}

.menutext {
    text-align: center;
    font-size: 30pt;
    line-height: 150%;
    
}

.menutext h2 {
    margin: 0px;
    text-align: center;
    font-family: eight-bit madness;
  
}

.menutext li {
    list-style: none;
    font-family: eight-bit madness;

}

a:link {
    text-decoration: none;
    color: white;
}

a:visited {
    color: white;
}
a:hover {
    color: #bc7325;
}

a:active {
    color: #e59c4e;
}

/*END NAV CODE*/
