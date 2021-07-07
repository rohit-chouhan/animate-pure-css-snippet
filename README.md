

<p align="center">
  <a href="https://animate.style/">
    <img src="https://www.drupal.org/files/project-images/animate.png" alt="">
  </a>
</p>

<p align="center">
  A snippet extention for Visual Studio, Which can convert <strong>Animate.css</strong> class to pure css code.'
</p>

## Snippet Extention for VS Code
Install From Here [https://marketplace.visualstudio.com/items?itemName=rohit-chouhan.animate-css](https://marketplace.visualstudio.com/items?itemName=rohit-chouhan.animate-css)

## Usage
If you add:
```html
animate__bounce
```
It will convert to:
```css
 @-webkit-keyframes bounce {
 	from 20% 53% to {
 		-webkit-animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		-webkit-transform: translate3d(0, 0, 0);
 		transform: translate3d(0, 0, 0);
 	}
 	40% 43% {
 		-webkit-animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		-webkit-transform: translate3d(0, -30px, 0) scaleY(1.1);
 		transform: translate3d(0, -30px, 0) scaleY(1.1);
 	}
 	70% {
 		-webkit-animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		-webkit-transform: translate3d(0, -15px, 0) scaleY(1.05);
 		transform: translate3d(0, -15px, 0) scaleY(1.05);
 	}
 	80% {
 		-webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		-webkit-transform: translate3d(0, 0, 0) scaleY(0.95);
 		transform: translate3d(0, 0, 0) scaleY(0.95);
 	}
 	90% {
 		-webkit-transform: translate3d(0, -4px, 0) scaleY(1.02);
 		transform: translate3d(0, -4px, 0) scaleY(1.02);
 	}
 }
 @keyframes bounce {
 	from 20% 53% to {
 		-webkit-animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		-webkit-transform: translate3d(0, 0, 0);
 		transform: translate3d(0, 0, 0);
 	}
 	40% 43% {
 		-webkit-animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		-webkit-transform: translate3d(0, -30px, 0) scaleY(1.1);
 		transform: translate3d(0, -30px, 0) scaleY(1.1);
 	}
 	70% {
 		-webkit-animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		animation-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
 		-webkit-transform: translate3d(0, -15px, 0) scaleY(1.05);
 		transform: translate3d(0, -15px, 0) scaleY(1.05);
 	}
 	80% {
 		-webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
 		-webkit-transform: translate3d(0, 0, 0) scaleY(0.95);
 		transform: translate3d(0, 0, 0) scaleY(0.95);
 	}
 	90% {
 		-webkit-transform: translate3d(0, -4px, 0) scaleY(1.02);
 		transform: translate3d(0, -4px, 0) scaleY(1.02);
 	}
 }
 .animate__bounce {
 	-webkit-animation-name: bounce;
 	animation-name: bounce;
 	-webkit-transform-origin: center bottom;
 	transform-origin: center bottom;
 	animation-duration: 1s;
 	-webkit-animation-duration: 1s;
 	animation-iteration-count: infinite;
 	-webkit-animation-iteration-count: infinite;
 }
```

<hr/>


<p align="center">
  <a href="https://animate.style/">
    <img src="https://www.drupal.org/files/project-images/animate.png" alt="">
  </a>
</p>

<p align="center">
  A complete css class snippet for <strong>Animate.css</strong>
</p>

## Snippet Extention for VS Code
Install From Here [https://marketplace.visualstudio.com/items?itemName=rohit-chouhan.animate-css-snippet](https://marketplace.visualstudio.com/items?itemName=rohit-chouhan.animate-css-snippet)

<p align="center">
  <a href="https://animate.style/">
    <img src="https://i.ibb.co/RQnyjDk/ezgif-com-gif-maker-1.gif" alt="">
  </a>
</p>

## Usage
If you add:
```html
acss__bounce

acss__<class_of_animate_css>
```
It will convert to:
```css
animate__animated animate__bounce animate__slower animate__infinite animate__delay-2s
```
### Hello,
This snippet developed by [Rohit Chouhan](https://www.linkedin.com/in/itsrohitchouhan/), Contact: [me@rohitchouhan.com](mailto:me@rohitchouhan.com)
