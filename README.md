# Optimization-and-Differential-Equation

I optimized the length, width, and height for a box without a lid keeping the surface area constant to 100 meters squared. I solved this optimization problem two ways. First, I used calculus to optimize the dimensions. After ﬁnding the dimensions using pen and paper I wanted to solve it numerically in Python using the built in minimize function from the package scipy.optimize. After coding it up I found the dimensions of the box to be exactly those that I found by using calculus methods. 

I investigated the time evolution of a damped oscillator that experienced an impulsive driving force that could’ve taken the form of a Heaviside step function or an impulse delta function. The amplitude of the oscillator drops as time progresses. I plotted the diﬀerential equation in Python and solved it with the scipy.integrate package using the function odeint.
