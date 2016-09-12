# svg

## demo
> 绘制一个圆：1.svg

```svg
<circle cx="100" cy="50" r="40" stroke="black" stroke-width="2" fill="red"/>
```

> 矩形，透明度，圆角：2.svg

```svg
<rect x="300" y="100" width="250" height="250" style="fill:blue;stroke:pink;stroke-width:5;
fill-opacity:0.1;stroke-opacity:0.9"/>
<!--rx 和 ry 属性可使矩形产生圆角-->
<rect x="550" y="0" rx="20" ry="20" width="250" height="100" style="fill:red;stroke:black;
stroke-width:5;opacity:0.5"/>
```

> 椭圆：3.svg

```svg
<!-- 椭圆有不同的 x 和 y 半径，而圆的 x 和 y 半径是相同的 -->
<ellipse cx="300" cy="150" rx="150" ry="80" style="fill:rgb(200,100,50);stroke:rgb(0,0,100);stroke-width:2"/>
```

> 线条：4.svg

```svg
<!-- 起点x1y1，终点x2y2 -->
<line x1="0" y1="0" x2="300" y2="300" style="stroke:rgb(99,99,99);stroke-width:2"/>
```

> 三角形，多边形：5.svg

```svg
<!-- 三角形 -->
<polygon points="640,351 600,210 770,20" style="fill:#FF9800; stroke:#795548;stroke-width:2"/>
<!-- 四边形 -->
<polygon points="420,100 500,210 410,320 323,234" style="fill:#cccccc;stroke:#000000;stroke-width:1"/>
<!-- 五角星 -->
<polygon points="100,10 40,180 190,60 10,60 160,180" style="fill:#F44336;stroke:#F44336;fill-rule:nonzero;" />
```

> svg编辑器创建：6.svg

- 通过AI钢笔工具绘制，导出svg格式

```svg
<?xml version="1.0" encoding="utf-8"?>
<!-- Generator: Adobe Illustrator 19.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
<svg version="1.1" id="图层_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 960 560" style="enable-background:new 0 0 960 560;" xml:space="preserve">
    <style type="text/css">
    .st0 {
        fill: #FFFFFF;
        stroke: #000000;
        stroke-miterlimit: 10;
    }
    </style>
    <path id="XMLID_1_" class="st0" d="M77,82c76.3,259.8,128.7,318.6,164,316c54.2-3.9,54.3-150.9,149-183c88.7-30.1,153.1,77.2,266,74
	c67.3-1.9,158.3-43.3,264-214" />
</svg>
```
> 折线：7.svg
```svg
<!-- 折线，当然也可以画直线 -->
<polyline points="100,100 200,100 200,200 300,200" style="fill:white;stroke:red;stroke-width:2"/>
```

> path应用：8.svg

- M = moveto      
- L = lineto      
- H = horizontal lineto     
- V = vertical lineto     
- C = curveto     
- S = smooth curveto     
- Q = quadratic Belzier curve      
- T = smooth quadratic Belzier curveto      
- A = elliptical Arc     
- Z = closepath     

```svg
<path d="M100 100 L200 100 L200 200 L300 200" style="fill:white;stroke:green;stroke-width:2"/>
```

> 滤镜使用：9.svg

- feBlend      
- feColorMatrix      
- feComponentTransfer     
- feComposite    
- feConvolveMatrix    
- feDiffuseLighting       
- feDisplacementMap      
- feFlood        
- feGaussianBlur     
- feImage     
- feMerge    
- feMorphology    
- feOffset     
- feSpecularLighting    
- feTile    
- feTurbulence    
- feDistantLight    
- fePointLight       
- feSpotLight       













## 资源
- w3school:
http://www.w3school.com.cn/svg/index.asp
- svg类库snap.svg.js，像操作dom一样操作svg资源
http://snapsvg.io
- 基本的svg动画
https://msdn.microsoft.com/zh-cn/library/gg193979
