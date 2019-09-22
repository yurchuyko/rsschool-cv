# Yurii Chuiko
#### urchuyko@gmail.com
#### +38(050)-366-1769
## Sumary
I have a great desire to finish RSSchool courses and start a Front-end Developer career, improve my skills in a friendly team and, in general, connect my life with programming.
I like to develop and learn new technologies, I study easily and work hard, responsible.
## Skills
* HTML5/CSS3
* JavaScript
* jQuery
* Git
## Code example
```javascript
let header = document.getElementById("header");
let headerHeight = document.getElementById("header").offsetHeight;
function scroll() {
	if (document.documentElement.scrollTop > headerHeight) {
		header.classList.add('fixed');
	} else {
		header.classList.remove('fixed');
	}
};
window.addEventListener('scroll', scroll);
openMenu.onclick = function() {
	menu.classList.toggle("active");
}
```