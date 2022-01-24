# Fun with CSS

In this project, you will experiment and implement fun layout with HTML and CSS  **ONLY**!

Yes, no JavaScript!

Enjoy!

## Tasks

### 0. Sprite languages

#advanced

By using this HTML:

```
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

And this image file:  [0-sprite.png](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=b98d486cf857222709646620added40efb7dfd1277dab956adcd9f29ed548157 "0-sprite.png")

Create  `0-styles.css`  and generate this layout:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=642475052d15820bfcaab0be40c01ccc9d50329428da89654e6162e1be79ecba)

You are not allowed to change the image and the HTML -  _sprite is cool!_

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `0-styles.css`

Done?  Help

### 1. Move the (under)line

#advanced

By using this HTML:

```
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

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1c6c1379369af6a7bc15b3c905ce203bc78705e2bb11d2c3c268b110b3c033fb)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `1-styles.css`

Done?  Help

### 2. Toggle

#advanced

By using this HTML:

```
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

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=af795bd522d6923250decc1235ee3e840c37660448693f01656aa986efda433b)

**Unchecked:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=86519d480bb2d1aecc82f3859643b2f3ce6b85cad8c37ba8cf3105a4e29b826d)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `2-styles.css`

Done?  Help

### 3. Menu

#advanced

By using this HTML:

```
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

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220124T020918Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a42c9167d6d71d4af12b62693e3b4134de2d201b351f0bc53b02b482451d17da)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `3-styles.css`
