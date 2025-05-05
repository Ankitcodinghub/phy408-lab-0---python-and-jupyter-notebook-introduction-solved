# phy408-lab-0---python-and-jupyter-notebook-introduction-solved
**TO GET THIS SOLUTION VISIT:** [Phy408 Lab 0 – Python and Jupyter notebook introduction Solved](https://www.ankitcodinghub.com/product/phy408-lab-0-python-and-jupyter-notebook-introduction-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100501&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Phy408 Lab 0 - Python and Jupyter notebook introduction Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Lab 0 – Python and Jupyter notebook introduction

In [ ]: %matplotlib inline import numpy as np

import matplotlib.pyplot as plt 1.1 1 Warm-up Exercises

Try the following commands on your jupyter notebook or python editor and see what output they produce.

In [ ]: a = 1 + 5 b=2

c=a+b print(a / b) print(a // b) print(a – b) print(a * b) print(a**b)

<pre>In [ ]: a = np.array([[3, 1],
                      [1, 3]])
</pre>
<pre>        b = np.array([[3],
                      [5]])
</pre>
<pre>        print(a * b)
        print(np.dot(a, b))
        print(np.dot(b.T, a))
        c = a**(-1.0)
        print(c * a)
</pre>
<pre>In [ ]: t = np.arange(10)
        g = np.sin(t)
</pre>
<pre>        h = np.cos(t)
        plt.figure()
        plt.plot(t, g, 'k', t, h, 'r');
</pre>
<pre>        t = np.arange(0, 9.1, 0.1)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<pre>        g = np.sin(t)
        h = np.cos(t)
        plt.figure()
        plt.plot(t, g, 'ok', t, h, '+r');
</pre>
<pre>In [ ]: t = np.linspace(0, 10, 20)
        print(t)
</pre>
<pre>        t = np.logspace(0.001, 10, 9)
        print(t)
        t = np.logspace(-3, 1, 9)
        print(t)
</pre>
<pre>        y = np.exp(-t)
</pre>
<pre>        plt.figure()
        plt.plot(t, y, 'ok')
        plt.figure()
        plt.semilogy(t, y, 'ok')
</pre>
1.2 2 Integration Function

Here is a more complicated function that computes the integral y(x) with interval dx:

∫

</div>
</div>
<div class="layoutArea">
<div class="column">
sampled time series (even.py).

</div>
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
N y(x)dx ∼ ∑yidxi.

</div>
</div>
<div class="layoutArea">
<div class="column">
c =

It can deal with both cases of even and uneven sampling.

In [1]: def integral(y, dx):

# function c = integral(y, dx)

# To numerically calculate integral of vector y with interval dx: # c = integral[ y(x) dx]

# —— This is a demonstration program ——

n = len(y) # Get the length of vector y

nx = len(dx) if np.iterable(dx) else 1

c = 0 # initialize c because we are going to use it # dx is a scalar &lt;=&gt; x is equally spaced

if nx == 1: # ==, equal to, as a condition

for k in range(1, n):

c = c + (y[k] + y[k-1]) * dx / 2

<pre>            # x is not equally spaced, then length of dx has to be n-1
</pre>
elif nx == n-1:

for k in range(1, n):

c = c + (y[k] + y[k-1]) * dx[k-1] / 2

# If nx is not 1 or n-1, display an error messege and terminate program else:

print(‘Lengths of y and dx do not match!’) return c

Save this program as integral.py. Now we can call it to compute ∫ π sin(t)dt with an evenly

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
In [ ]: # number of samples nt = 100

<pre>        # generate time vector
</pre>
t = np.linspace(0, np.pi, nt)

# compute sample interval (evenly sampled, only one number) dt = t[1] – t[0]

y = np.sin(t)

plt.plot(t, y, ‘r+’)

c = integral(y, dt)

print(c)

1.2.1 Part 1

First plot y(t). Is the output c value what you are expecting for ∫ π sin(t)dt? How can you improve

</div>
</div>
<div class="layoutArea">
<div class="column">
the accuracy of your computation?

1.2.2 Part 2

</div>
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
For an unevenly spaced time series that depicts sin[2π(8t − 4t2)], the so-called chirp function, compute ∫ 1 sin[2π(8t − 4t2)]dt (saved as uneven.py).

0

In [ ]: nt = 20

# sampling between [0,0.5]

t1 = np.linspace(0, 0.5, nt)

# double sampling between [0.5,1]

t2 = np.linspace(0.5, 1, 2*nt)

# concatenate time vector

t = np.concatenate((t1[:-1], t2))

# compute y values

y = np.sin(2 * np.pi * (8*t – 4*t**2)) plt.plot(t, y)

# compute sampling interval vector

dt = t[1:] – t[:-1]

c = integral(y, dt)

print(c)

Show your plot of y(t) (for nt = 50). Try different nt values and see how the integral results change. Write a for loop around the statements above to try a series of nt values (e.g, 20, 50, 100, 500, 1000) and generate a plot of c(nt). What value does c converge to after using larger and larger nt? (Please include your modified Python code.)

1.3 3 Accuracy of Sampling

Let us sample the function g(t) = cos(2π f t) at sampling interval dt = 0.5, for frequency values of f = 0, 0.25, 0.5, 0.75, 1.0, 1.5, 2.0 hertz.

In each case, plot on the screen the points of the resulting time series (as isolated red crosses) to see how well it approximates g(t) (plotted as a blue-dotted line, try a very small dt fine sampling). Submit only plots for frequencies of 0.25 and 0.75 Hertz, use xlabel, ylabel, title commands to annotate each plot. For each frequency that you investigated, do you think the sampling time

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
series is a fair representation of the original time series g(t)? What is the apparent frequency for the sampling time series? (Figure out after how many points (N) the series repeats itself, then the apparent frequency = 1/(N*dt). You can do this either mathematically or by inspection. A flat time series has apparent frequency = 0.) Can you guess with a sampling interval of dt = 0.5, what is the maximum frequency f of g(t) such that it can be fairly represented by the discrete time series? (Please attach your Python code.)

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
