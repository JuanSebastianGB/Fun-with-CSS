# Fun with CSS

## Tasks

### 0. Sprite languages

#advanced

By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>

```

And this image file:  [0-sprite.png](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=2019cb0e70c0ec566e57f2d0b2d39ee4d9c3df2942992aabfd4e8211f80f199a "0-sprite.png")

Create  `0-styles.css`  and generate this layout:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=afbaebe05c7da1666389f5f7e92c71f005ecaa2f85879ea107782d0933982389)

You are not allowed to change the image and the HTML -  _sprite is cool!_

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `0-styles.css`



### 1. Move the (under)line


By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>

```

Create  `1-styles.css`  and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e3f23da8b563c4167728ba89fe93e4d8e0c4022b77b44e37698bfad5b48828fe)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `1-styles.css`



### 2. Toggle



By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>

```

Create  `2-styles.css`  and generate this layout where the  `<input>`  is has this custom toggle layout:

**Checked:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3fb615ed4801f39a211d93f8ab96773fb4db6f5e4ff3214f5a1362a6394d0af8)

**Unchecked:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dac61685b0bd12d127bf48ebf4bd822a8ab2fb7432b5901a68de6b0484060cc5)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `2-styles.css`

### 3. Menu


By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>

```

Create  `3-styles.css`  and generate this layout/animation:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220525%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220525T031009Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=62384b4210b05a5e65115a0f279e74e9c0137e525fb441443663714a5fbac3db)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `3-styles.css`


Copyright © 2022 Holberton Inc, All rights reserved.