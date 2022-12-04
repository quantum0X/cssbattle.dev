![133](img/133.png)

```css
<div id="x"><div id="a"><div id="b"></div></div>
<div id="a"><div id="d"></div></div></div>
<style>
*{margin:0;background:#F5D6B4}
#x{height:300;width:400;display:flex;flex-direction:column}
#b,#d{width:40;height:40;margin:110 auto;border:20px solid#d86f45;border-radius:50%;box-shadow:0 0 0 20px#f5d6b4,0 0 0 40px#d86f45;}
#a{height:50%;overflow:hidden;}
#d{margin:-60 120;height:80;width:80}
#d::before{content:'';position:absolute;height:20;width:20;background:#D86F45;border-radius:50%;margin:29 20;box-shadow:-80px 0 0#D86F45}
```


