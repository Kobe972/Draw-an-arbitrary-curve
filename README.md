# Draw-an-arbitrary-curve
In disgusting physics experiment of USTC,fitting the data into a curve is sometimes a terrible thing.This program helps you to fit any sequence of points into a curve.

## Introduction
draw.exe is the executive file of draw.py.However,it starts slower.This file in order to enables those who have installed tensorflow not compatible to mine to execute my program.

## Usage
In order to use this program flexibly,you can import curve.py in your own program.Function curve(data1,data2,x_label='x',y_label='y',title='Untitled') can draw the curve,and show the value of loss function in IDLE.data1 is array of the variables on x-axis,and data2 is that on y_axis.Other 3 parameters are easy to understand.

For example,this program draws a curve:
`<import curve
x=[1,2,3,4,5]
y=[1,4,9.1,16,25]
curve(x,y)>`

can fit x and y into a curve similar to y=x².

curve.py uses a neural network with the active function sigmoid(x)=1/(1+exp(-x)) to fit the curve.The network has two latent layers,with dimensions of 10 and 5 respectively.The plot redraws after every 50 iterations.

Writing a report is deadly boring.However,a great method can add fun and make use of your time.
