### g.raphael
---
https://github.com/DmitryBaranovskiy/g.raphael

https://github.com/takagotch/gRaphael

```
<svg width="80" heigth="80">
<circle cx="40" cy="40" r="30" stroke="#000" stroke-width="1" fill="#FFF" />
</svg>

<div id="container"></div>
<script src="http://cdnjs.cloudflare.com/ajax/libs/raphael/2.1.0/raphael-min.js"></script>
<script>
var paper = Rapael("container", 500, 300);
var dot = paper.circle(250, 150, 30).attr({
  fill: "#FFF",
  stroke: "#000",
  "stroke-width": 1
});
</script>

window.onload = function(){
  var paper = new Raphael("container", 500, 300);
  for(var i = 0; i < 5; i+=1){
    var ultiplier = i*5;
    paper.circle(250 + (2*multiplier), 150 + multiplier, 50 = multiplier)
  }
}

var dot = paper.circle(250, 150, 30).attr({
  gradient: '90-#000=#FF0000',
  stroke: '#000',
  'stroke-width': 3,
  'stroke-linejoin': 'round',
  rotation: -120
});
```

```
```

```
```


