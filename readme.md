# Star BG 🌟

## Implement Star BG with JavaScript

```
   <script src="https://unpkg.com/star-bg@1.1.0/starbg.min.js" defer></script>
<script>
    var stars = new STAR();
    stars.init();
</script>
```

### Options

```
   <script src="https://unpkg.com/star-bg@1.1.0/starbg.min.js" defer></script>
<script>
    var stars = new STAR();
    stars.init({
        color:'#fff', //colors of stars
        opacity: 0.4 // Opacity of stars
    });
</script>
```

### Destroy Stars
```
   <script src="https://unpkg.com/star-bg@1.1.0/starbg.min.js" defer></script>
<script>
    var stars = new STAR();
    stars.init({
        color:'#fff', //colors of stars
        opacity: 0.4 // Opacity of stars
    });
    stars.destroy();
</script>
```

## Implement Star BG with CSS & HTML
### link the stylesheet
```
<link rel="stylesheet" href="https://unpkg.com/star-bg@1.1.0/starbg.min.css" />
```
### Add these to the top of the body
```
<div class="stars" id="star-layer1"></div>
<div class="stars" id="star-layer2"></div>
<div class="stars" id="star-layer3"></div>
```
### Add this to your stylesheet
```
:root{
    --starColor: #fff; /* Star Colors*/
}
.stars{
    opacity: 0.4;
}
```