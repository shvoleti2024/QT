---
title: "Welcome"
description: "Welcome Post"
author: "J004-Vansh Lata, Siddhartha Hrishikesha Voleti and Madhvikaben Vasava"
date: "2/25/2025"
---


# Welcome

**Hello world**, this is my first blog post.

I can write in markdown

```python
import funix
import matplotlib.pyplot as plt
import matplotlib.figure
import numpy

def Plot_Graphs(Function: funix.hint.Literal['A*tan(kx+c)', 'A*sin(kx+c)', "A*cos(kx+c)"],A: funix.hint.FloatSlider(0, 8, 0.1), k: funix.hint.FloatSlider(0, 10, 0.1), c: funix.hint.FloatSlider(0, 2*numpy.pi, 0.01),Colour: funix.hint.Literal['Blue', 'Green', 'Red','Black','Purple']) -> matplotlib.figure.Figure:
    fig=plt.figure()
    fn=Function
    x = numpy.linspace(0, 20, 200)
    if fn=="A*tan(kx+c)":
        plt.plot(x,A*(numpy.tan((k*x)+c)),color=Colour)
        plt.ylabel(f"{A}tan({k}x+{c})")
    elif fn=="A*sin(kx+c)":
        plt.plot(x,A*(numpy.sin((k*x)+c)),color=Colour)
        plt.ylabel(f"{A}sin({k}x+{c})")
    else:
        plt.plot(x,A*(numpy.cos((k*x)+c)),color=Colour)
        plt.ylabel(f"{A}cos({k}x+{c})")
    plt.xlabel("X-axis")
    
    return fig
```

I can also write math equations:

$$
y = x^2
$$


I can create lists easily:

- One
- Two

I can also create numbered lists:

1. One
2. Two


Or, create a table:

| Name  | Age |
|-------|-----|
| Alice | 20  |
| Bob   | 21  |

