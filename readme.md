## Table of contents

- [Overview](#overview)
- [Links](#links)
- [My process](#my-process)
[Built with](#built-with)
- [Author](#author)




## Overview

I built out this QR code component and get it looking as close to the design as possible from frontendmentor.

This is just a challenge

### Links

- Live Site URL: https://leafy-dodol-a73d9e.netlify.app

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

<!-- html -->


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit&display=swap" rel="stylesheet">
    <title>QR Component</title>
</head>
<body>
    <div class="white-box">
        <div class="blue-box">
            <img src="png/image-qr-code.png" alt="pg">
        </div>

        <div class="text">
            <h3>Improve your front-end skills by building projects</h3>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>

    </div>
</body>
</html>

<!-- css -->

body{
    background-color: hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
}

.white-box{
    background-color: white;
    height: 390px;
    width: 260px;
    align-items: center;
    position: relative;
    left: 550px;
    top: 120px;
    border-radius: 15px;
}

.blue-box{
    height: auto;
    width: 100%;
    position: absolute;
    padding: 10px 10px 0px 12px;
}

.blue-box img{
    height: 90%;
    width: 90%;
    border-radius: 15px;
}

.text{
    padding: 250px 28px 0px 28px;
    text-align: center;
}

.text h3{
    font-weight: 700;
    color: hsl(218, 44%, 22%);
    font-size: 16px;
}

.text p{
    font-weight: 400;
    font-size: 13px;
    color: hsl(216, 3%, 66%);
}

## Author

- Email - [adeyemimeshack@gmail.com]
- Frontend Mentor - [@the20thshakk](https://https://www.frontendmentor.io/profile/the20thshakk)
- Twitter - [@the20thshakk]
