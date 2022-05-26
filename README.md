##### This is my first SASS project.
## What did I learn in this project?
* First of all, I took apart the website that I was planning to build.
* I gave the necessary command in the terminal so that what I did with SASS would affect my page. 
* sass --watch main.scss:style.css
* I assigned the colors I will use, the background image, and the font-family variables. Ex:
* $primary-color:#272727;
* $font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
* $main-bgImage-path: '../img/model-1.jpg';
* I created @mixin to call and use it in the necessary settings.
* I learned that using mixin works like a function. Ex:
* @mixin transition($sec) {transition: all $sec;}
* @mixin bgImage($height, $url) {
    height: $height;
    width: 100%;
    background: linear-gradient(
        to right,
        rgba($primary-color, 0.9),
        rgba($primary-color, 0.3)
    ),
    url($url);
    background-position: center center;
    background-size: cover;
}
* It is very easy to create a responsive structure using SASS and apply it separately for each page.
* I used flex constructs frequently throughout the project.
* Using ::after I added a div that creates opacity over the images on my page.
### This project is a really cool project for SASS. I am happy to have done this project. 😎
