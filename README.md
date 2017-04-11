<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>css border</title>
</head>
<style>
  p.none {border-style:none;} /* 默认无边框 */
  p.dotted {border-style:dotted;} /* 点线框 */
  p.dashed {border-style:dashed;} /* 虚线框 */
  p.solid {border-style:solid;} /* 实线边界 */
  p.double {borser-style:double;} /* 两个边界 */
  p.groove {border-style:groove;} /* 3D沟槽边界 */
  p.ridge {border-style:ridge;} /* 3D脊边界 */
  p.inset {borser-style:inset;} /* 3D的嵌入边框 */
  p.outset {border-style:outset;} /* 3D的突出边框 */
  p.hidden {border-style:hidden;}
  p.one {border-style:solid;border-width:5px;} /* 边框宽度 */
  p.two {border-style:solid;border-width:medium;}
  p.three {border-style:solid;border-width:1px;}
</style>
<body>
<p class="none">no border</p>
<p class="dotted">a dotted border</p>
<p class="dashed">a dashed border</p>
<p class="solid">a solid border</p>
<p class="double">a double border</p>
<p class="groove">a groove border</p>
<p class="ridge">a ridge border</p>
<p class="inset">an inset border</p>
<p class="outset">an outset border</p>
<p class="hidden">a hidden border</p>
<p class="one">some text</p>
<p class="two">some text</p>
<p class="three">some text</p>
<p><b>注意：</b> "border-width" 属性 如果单独使用则不起作用. 要先使用 "border-style" 属性来设置 borders .</p>
</body>
</html>
