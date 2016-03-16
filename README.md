# canvas
<a href="http://htmlpreview.github.io/?https://github.com/wy-ang/canvas/blob/demo/game.html">game.html  >>小游戏demo</a>  

<a href="http://htmlpreview.github.io/?https://github.com/wy-ang/canvas/blob/demo/demo.html">demo.html  >>小demo</a>

http://htmlpreview.github.com/



<h5>附录：</h5>
<h6>颜色、样式和阴影</h6>
<table class="dataintable" style="height: 160px; width: 1200px;">
<tbody>
<tr><th>属性</th><th>描述</th></tr>
<tr>
<td>fillStyle</td>
<td>设置或返回用于填充绘画的颜色、渐变或模式</td>
</tr>
<tr>
<td>strokeStyle</td>
<td>设置或返回用于笔触的颜色、渐变或模式</td>
</tr>
<tr>
<td>shadowColor</td>
<td>设置或返回用于阴影的颜色</td>
</tr>
<tr>
<td>shadowBlur</td>
<td>设置或返回用于阴影的模糊级别</td>
</tr>
<tr>
<td>shadowOffsetX</td>
<td>设置或返回阴影距形状的水平距离</td>
</tr>
<tr>
<td>shadowOffsetY</td>
<td>设置或返回阴影距形状的垂直距离</td>
</tr>
</tbody>
</table>
<table class="dataintable" style="height: 114px; width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>createLinearGradient()</td>
<td>创建线性渐变（用在画布内容上）</td>
</tr>
<tr>
<td>createPattern()</td>
<td>在指定的方向上重复指定的元素</td>
</tr>
<tr>
<td>createRadialGradient()</td>
<td>创建放射状/环形的渐变（用在画布内容上）</td>
</tr>
<tr>
<td>addColorStop()</td>
<td>规定渐变对象中的颜色和停止位置</td>
</tr>
</tbody>
</table>
<div>
<h6>线条样式</h6>
<table class="dataintable" style="height: 114px; width: 1200px;">
<tbody>
<tr><th>属性</th><th>描述</th></tr>
<tr>
<td>lineCap</td>
<td>设置或返回线条的结束端点样式</td>
</tr>
<tr>
<td>lineJoin</td>
<td>设置或返回两条线相交时，所创建的拐角类型</td>
</tr>
<tr>
<td>lineWidth</td>
<td>设置或返回当前的线条宽度</td>
</tr>
<tr>
<td>miterLimit</td>
<td>设置或返回最大斜接长度</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>矩形</h6>
<table class="dataintable" style="height: 114px; width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>rect()</td>
<td>创建矩形</td>
</tr>
<tr>
<td>fillRect()</td>
<td>绘制&ldquo;被填充&rdquo;的矩形</td>
</tr>
<tr>
<td>strokeRect()</td>
<td>绘制矩形（无填充）</td>
</tr>
<tr>
<td>clearRect()</td>
<td>在给定的矩形内清除指定的像素</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>路径</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>fill()</td>
<td>填充当前绘图（路径）</td>
</tr>
<tr>
<td>stroke()</td>
<td>绘制已定义的路径</td>
</tr>
<tr>
<td>beginPath()</td>
<td>起始一条路径，或重置当前路径</td>
</tr>
<tr>
<td>moveTo()</td>
<td>把路径移动到画布中的指定点，不创建线条</td>
</tr>
<tr>
<td>closePath()</td>
<td>创建从当前点回到起始点的路径</td>
</tr>
<tr>
<td>lineTo()</td>
<td>添加一个新点，然后在画布中创建从该点到最后指定点的线条</td>
</tr>
<tr>
<td>clip()</td>
<td>从原始画布剪切任意形状和尺寸的区域</td>
</tr>
<tr>
<td>quadraticCurveTo()</td>
<td>创建二次贝塞尔曲线</td>
</tr>
<tr>
<td>bezierCurveTo()</td>
<td>创建三次方贝塞尔曲线</td>
</tr>
<tr>
<td>arc()</td>
<td>创建弧/曲线（用于创建圆形或部分圆）</td>
</tr>
<tr>
<td>arcTo()</td>
<td>创建两切线之间的弧/曲线</td>
</tr>
<tr>
<td>isPointInPath()</td>
<td>如果指定的点位于当前路径中，则返回 true，否则返回 false</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>转换</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>scale()</td>
<td>缩放当前绘图至更大或更小</td>
</tr>
<tr>
<td>rotate()</td>
<td>旋转当前绘图</td>
</tr>
<tr>
<td>translate()</td>
<td>重新映射画布上的 (0,0) 位置</td>
</tr>
<tr>
<td>transform()</td>
<td>替换绘图的当前转换矩阵</td>
</tr>
<tr>
<td>setTransform()</td>
<td>将当前转换重置为单位矩阵。然后运行 transform()</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>文本</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>属性</th><th>描述</th></tr>
<tr>
<td>font</td>
<td>设置或返回文本内容的当前字体属性</td>
</tr>
<tr>
<td>textAlign</td>
<td>设置或返回文本内容的当前对齐方式</td>
</tr>
<tr>
<td>textBaseline</td>
<td>设置或返回在绘制文本时使用的当前文本基线</td>
</tr>
</tbody>
</table>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>fillText()</td>
<td>在画布上绘制&ldquo;被填充的&rdquo;文本</td>
</tr>
<tr>
<td>strokeText()</td>
<td>在画布上绘制文本（无填充）</td>
</tr>
<tr>
<td>measureText()</td>
<td>返回包含指定文本宽度的对象</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>图像绘制</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>drawImage()</td>
<td>向画布上绘制图像、画布或视频</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>像素操作</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>属性</th><th>描述</th></tr>
<tr>
<td>width</td>
<td>返回 ImageData 对象的宽度</td>
</tr>
<tr>
<td>height</td>
<td>返回 ImageData 对象的高度</td>
</tr>
<tr>
<td>data</td>
<td>返回一个对象，其包含指定的 ImageData 对象的图像数据</td>
</tr>
</tbody>
</table>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>createImageData()</td>
<td>创建新的、空白的 ImageData 对象</td>
</tr>
<tr>
<td>getImageData()</td>
<td>返回 ImageData 对象，该对象为画布上指定的矩形复制像素数据</td>
</tr>
<tr>
<td>putImageData()</td>
<td>把图像数据（从指定的 ImageData 对象）放回画布上</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>合成</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>属性</th><th>描述</th></tr>
<tr>
<td>globalAlpha</td>
<td>设置或返回绘图的当前 alpha 或透明值</td>
</tr>
<tr>
<td>globalCompositeOperation</td>
<td>设置或返回新图像如何绘制到已有的图像上</td>
</tr>
</tbody>
</table>
</div>
<div>
<h6>其他</h6>
<table class="dataintable" style="width: 1200px;">
<tbody>
<tr><th>方法</th><th>描述</th></tr>
<tr>
<td>save()</td>
<td>保存当前环境的状态</td>
</tr>
<tr>
<td>restore()</td>
<td>返回之前保存过的路径状态和属性</td>
</tr>
<tr>
<td>createEvent()</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>getContext()</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>toDataURL()</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>











