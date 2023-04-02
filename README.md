# Computing power plot

The aim of this project is to create a beautiful plot of the evolution of the
computer power.
It should have some photos and look nice.  
It should also have predictions for the next decade. Having estimation of the
human brain capacity will be nice.

## Inspiration

https://pages.experts-exchange.com/processing-power-compared  
This is a nice source but it is not a xy plot. However it has sources that could
be useful.

http://www.jetpress.org/volume1/moravec.htm  
This is the bible, I wan't to do something like this but updated and with more
info.

http://www.donbot.com/Futurebot/NewTech/NT01370MoravecsGraphUpdated2020.html  
Update of moravec plot but with small added information.

https://www.karlrupp.net/2013/06/cpu-gpu-and-mic-hardware-characteristics-over-time/  
This one is nice because it has a repository on github with the data available.

Maybe I should look for more specific data: gpu, cpu, supercomputer...

### Gpu

The best I find is [karlrupp](https://www.karlrupp.net/2013/06/cpu-gpu-and-mic-hardware-characteristics-over-time/).

I will have to add data from the new gpus. One source is the [wikipedia page](https://en.wikipedia.org/wiki/List_of_Nvidia_graphics_processing_units).

### Cpu

Again karkupp is the best.

### Supercomputer

top500.org is the website of reference. The best plot for my task is the following:  
https://www.top500.org/statistics/perfdevel/  
There I can get the values to build a new plot.

## Building

### Data collection

The first stage is to collect data. I will prepare csv files with the data, 
and that way I could update the chart in the future if needed.

### Plot enhance

I already have a plot with the data and the projections. Now I want to add more data:

* Label some of the points with the name of the computer
* Add name to the scales, peta, hexa...
* Add the computing power of the brain of different animals

https://matplotlib.org/examples/pylab_examples/demo_annotation_box.html  
https://matplotlib.org/users/text_intro.html  
This tutorials could be helpful.
