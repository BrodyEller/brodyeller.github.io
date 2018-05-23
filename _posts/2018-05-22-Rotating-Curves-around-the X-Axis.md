---
layout: post
title:  "Rotating Curves around the X-Axis"
date:   2018-05-22 08:52:19 -0400
categories: post
header_image: background_generic.png
excerpt: You can use the integral of a curve to calculate the volume of an area by rotating it around an axis.
published: true
---
  
You can use the integral of a curve to calculate the volume of an area by rotating it around an axis.

When you find an integral, you find the area under a curve.  If you were to take an integral at a single point on a curve, you'd get it's distance from the x-axis.  You can then take this distance and put it into the equation for area of a circle, $$ \pi r^2 $$.

![Area of a Circle Revolution]({{site.url}}/{{site.images_folder}}/revolutions_gif_1.gif)

Building on this, if you find a definite integral across a certain range, you can use that value to find the volume of a solid revolved around the x-axis.

![Area of a Circle Revolution]({{site.url}}/{{site.images_folder}}/revolutions_gif_2.gif)

To use a definite integral in the equation for area of a circle, replace *r* with the definite integral resulting in this:

> $$ \pi \int^{a}_{b}{x^2 dx}$$

where x represents the function of the curve. Then, solve the expression for the volume of the solid formed by rotating the curve around the x-axis.

### Examples

1. Find the volume of the solid formed by rotating the equation $$ f(x)=x^2 $$ around the x-axis from $$ x=0 $$ to $$ x=4 $$.
	1. Plug $$ x^2 $$ into the formula for area of a circle: $$ \pi \int^{4}_{0}{(x^2)^2} $$
	2. Evaluate the definite integral: $$ \pi \frac{x^5}{5} \Bigr\|_{0}^{4} \approx 643.3982 $$
2. Find the volume of the solid formed by rotating the equation $$ f(x)=\sin{x} $$ between $$ x=0 $$ and $$ x=\pi $$.
	1. Plug $$ \sin{x} $$ into the formula for area of a circle: $$ \pi \int_{0}^{\pi}{\sin^2{x}} $$
	2. Evaluate the definite integral: $$ \frac{\pi\Bigl(x-\frac{\sin(2x)}{2}\Bigl)}{2} \Biggr\|_{0}^{\pi} \approx 4.9348 $$
		* See the full integration at [integral-calculator.com](https://www.integral-calculator.com/#expr=pi%2A%28sinx%29%5E2&lbound=0&ubound=pi)