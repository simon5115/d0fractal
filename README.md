# d0fractal
绘制分形图像

## Mandelbrot分形图像
根据Mandelbrot集绘制分形图像。Mandelbrot集由一个复变函数**f(z) = z<sup>2</sup> + c**生成，其中c为当前坐标点，z从0开始迭代。

Draw fractal image using Mandelbrot set. The Mandelbrot set is generated by a complex function **f(z) = z<sup>2</sup> + c**, where c is current coordinate point, and z iterates from 0.
![](https://github.com/d0t451/d0fractal/blob/master/images/mandelbrot.png)

## Julia分形图像
根据Julia集绘制分形图像。Julia集由一个复变函数**f(z) = z<sup>2</sup> + c**生成，其中c为常数，z从当前坐标点开始迭代。

Draw fractal images using Julia set. The Julia set is generated by a complex function **f(z) = z<sup>2</sup> + c**, where c is a constant, and z iterates from current coordinate point.
### c = (0.34-0.05i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(0.34-0.05j).png)
### c = (-0.52+0.62i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(-0.52+0.62j).png)
### c = (-0.54-0.5255i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(-0.54-0.5255j).png)
### c = (-0.55+0.64i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(-0.55+0.64j).png)
### c = (0.338+0.489i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(0.338+0.489j).png)
### c = (0.365-0.37i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(0.365-0.37j).png)
### c = (0.3593+0.5103i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(0.3593+0.5103j).png)
### c = (0.42413+0.20753i)
![](https://github.com/d0t451/d0fractal/blob/master/images/(0.42413+0.20753j).png)
### c = -1.38
![](https://github.com/d0t451/d0fractal/blob/master/images/-1.38.png)
### c = 1i
![](https://github.com/d0t451/d0fractal/blob/master/images/1j.png)

## Koch曲线分形图像
一个边长为1的等边三角形，取每边中间的三分之一，接上去一个形状完全相似的但边长为其三分之一的三角形，结果是一个六角形。取六角形的每个边做同样的变换，即在中间三分之一接上更小的三角形，以此重复，直至无穷。

The Koch snowflake can be constructed by starting with an equilateral triangle, then recursively altering each line segment as follows:
1. divide the line segment into three segments of equal length.
2. draw an equilateral triangle that has the middle segment from step 1 as its base and points outward.
3. remove the line segment that is the base of the triangle from step 2.

![](https://github.com/d0t451/d0fractal/blob/master/images/koch.png)

## 谢尔宾斯基地毯分形图像
将一个实心正方形划分为的9个小正方形，去掉中间的小正方形，再对余下的小正方形重复这一操作便能得到谢尔宾斯基地毯。

Divide a solid square into 9 small squares, remove the middle square, and repeat the operation for remaining small squares to get the Sierpinski carpet.

![](https://github.com/d0t451/d0fractal/blob/master/images/sierpinski_carpet.png)