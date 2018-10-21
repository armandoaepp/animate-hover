# animate-hover.css [![npm version](https://badge.fury.io/js/animate.css.svg)](https://www.npmjs.com/package/animate-hover)

Common CSS helper classes.

### CSS animate-hover Classes
Animaciones css Hovers: animaciones con efecto Hover css3


## Install

Install with Npm

### npm

To install with npm run

```bash
$ npm install animate-hover --save
```


## Basic Usage

1.  Include the stylesheet on your document's `<head>`

```html
<head>
  <link rel="stylesheet" href="css/animate-hover.min.css">
</head>
```

#### for animations based on animate.css

```html
<head>
  <link rel="stylesheet" href="css/animate.css/animate.min.css">
  <link rel="stylesheet" href="css/animate-hover.min.css">
</head>
```

2.  Add the class `ahvr-animated animated-box` to the element you want to animate.

3.  Finally you need to add one of the following classes:

| Class Name        |                    |                     |                      |
| ----------------- | ------------------ | ------------------- | -------------------- |
| `animated-bounce`          | `animated-flash`            | `animated-pulse`             | `animated-rubberBand`         |
| `animated-shake`           | `animated-headShake`        | `animated-swing`             | `animated-tada`               |
| `animated-wobble`          | `animated-jello`            | `animated-bounceIn`          | `animated-bounceInDown`       |
| `animated-bounceInLeft`    | `animated-bounceInRight`    | `animated-bounceInUp`        | `animated-bounceOut`          |
| `animated-bounceOutDown`   | `animated-bounceOutLeft`    | `animated-bounceOutRight`    | `animated-bounceOutUp`        |
| `animated-fadeIn`          | `animated-fadeInDown`       | `animated-fadeInDownBig`     | `animated-fadeInLeft`         |
| `animated-fadeInLeftBig`   | `animated-fadeInRight`      | `animated-fadeInRightBig`    | `animated-fadeInUp`           |
| `animated-fadeInUpBig`     | `animated-fadeOut`          | `animated-fadeOutDown`       | `animated-fadeOutDownBig`     |
| `animated-fadeOutLeft`     | `animated-fadeOutLeftBig`   | `animated-fadeOutRight`      | `animated-fadeOutRightBig`    |
| `animated-fadeOutUp`       | `animated-fadeOutUpBig`     | `animated-flipInX`           | `animated-flipInY`            |
| `animated-flipOutX`        | `animated-flipOutY`         | `animated-lightSpeedIn`      | `animated-lightSpeedOut`      |
| `animated-rotateIn`        | `animated-rotateInDownLeft` | `animated-rotateInDownRight` | `animated-rotateInUpLeft`     |
| `animated-rotateInUpRight` | `animated-rotateOut`        | `animated-rotateOutDownLeft` | `animated-rotateOutDownRight` |
| `animated-rotateOutUpLeft` | `animated-rotateOutUpRight` | `animated-hinge`             | `animated-jackInTheBox`       |
| `animated-rollIn`          | `animated-rollOut`          | `animated-zoomIn`            | `animated-zoomInDown`         |
| `animated-zoomInLeft`      | `animated-zoomInRight`      | `animated-zoomInUp`          | `animated-zoomOut`            |
| `animated-zoomOutDown`     | `animated-zoomOutLeft`      | `animated-zoomOutRight`      | `animated-zoomOutUp`          |
| `animated-slideInDown`     | `animated-slideInLeft`      | `animated-slideInRight`      | `animated-slideInUp`          |
| `animated-slideOutDown`    | `animated-slideOutLeft`     | `animated-slideOutRight`     | `animated-slideOutUp`         |
| `animated-heartBeat`       |

Full example:

Animate: All Box
```html
<h1 class="ahvr-animated animated-box animated-bounce">Example</h1>

<a href="#">
  <div class="ahvr-square ahvr-boxed-image ahvr-animated animated-box animated-bounce">
    <img class="img-fluid image" src="./images/img_avatar.png" alt="Avatar">
    <div class="overlay">
      <div class="middle">
        <i class="box-icon fa fa-soccer-ball-o"></i>
        <h4 class="box-title"> Soccer Team </h4>
        <p class="box-text"> Best Sports Features</p>
      </div>
    </div>
  </div>
</a>
```

Animate: Box Content
```html
<h1 class="ahvr-animated animated-box ">Example
  <span class="animated-bounce"> animated-bounce </span>
</h1>

<a href="#">
  <div class="ahvr-square ahvr-boxed-image ahvr-animated animated-box">
    <img class="img-fluid image" src="../../../images/img_avatar.png" alt="Avatar">
    <div class="overlay animated-bounce">
      <div class="middle">
        <i class="box-icon fa fa-soccer-ball-o"></i>
        <h4 class="box-title"> Soccer Team </h4>
        <p class="box-text"> Best Sports Features</p>
      </div>
    </div>
  </div>
</a>
```