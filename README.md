# Redmine openSUSE Themes

A free Redmine theme for modern browsers base on [PurpleMine 2](https://github.com/mrliptontea/PurpleMine2).

We add some modify to match what needed.

## Change colour base on colour pallete openSUSE.

on stylesheets/application.css

```
top  --> #2e3c68 #2f5361
bottom --> #455b9d #73ba25
```

```
:%s/#2e3c68/#2f5361/g
:%s/#455b9d/#73ba25/g
```

## Change Font
We need change font from "Helvetica Neue" to "Open Sans".

```
body {
 margin:0;
 padding:0;
 background-color:#fff;
 color:#555;
 font-family:"Helvetica Neue",Helvetica,Arial,freesans,sans-serif;
 font-size:14px;
 font-weight:normal;
 line-height:1.428571429
}
```

```
font-family:"Open Sans",Arial,freesans,sans-serif;
```
