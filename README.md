# CSS Day 1 - 100 Days CSS Project
The project is created mainly for CSS training purpose. This is day 1.

## Result
![Result Day1](https://github.com/vietdang7/css-day1/blob/master/img/day1_result.png "Result Day 1")

## Code Example
Here are some lines of example code:
1. index.html:
```html
<html>
  <head>
    <meta charset="utf-8">
    <title>CSS Challenge - Day 1</title>
    <link rel="stylesheet" href="../css/main.css">
  </head>
  <body>
    <div class="mainframe">
      <div class="center">
        <div class="number">
          <!-- First part number 1-->
          <div class="one-first"></div>

          <!-- Second part number 1 -->
          <div class="one-second"></div>

          <!-- Third number -->
          <div class="zero-first"></div>

          <!-- Fourth number -->
          <div class="zero-second"></div>


```

2. main.css:
```css
/* Import Google Font */
@import url('https://fonts.googleapis.com/css?family=Days+One|Great+Vibes');

/* .mainframe */
.mainframe {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 400px;
  height: 400px;
  margin-top: -200px;
  margin-left: -200px;
  border-radius: 5px;
  box-shadow: 1px 2px 10px 0px rgba(0,0,0,0.3);
  background: #0074D9;
  background: -webkit-linear-gradient(bottom left, #0074D9 30%, #4FC1E9 90%);
  background: -moz-linear-gradient(bottom left, #0074D9 30%, #4FC1E9 90%);
  background: -o-linear-gradient(bottom left, #0074D9 30%, #4FC1E9 90%);
  background: linear-gradient(to top right, #0074D9 30%, #4FC1E9 90%);

}
```


## Why I create this project?
Simply to improve my CSS skills. In my opinion, the best learning way is practice, practice and more practice.


## Getting Started
### Prerequisites
1. You will need to a code editor like [`Atom`](https://atom.io/)


### Installation
* Clone this project (Using `git`command: `https://github.com/vietdang7/css-day1.git` or through your GitDesktop application)


## Testing
* Open `index.html` with your favorite browser


## Built With
- HTML
- CSS

## Contribution
If you want to make contribution for this project, feel free to `fork` this project and make `pull request`

## License
- This project is licensed under the MIT license
