# Aircraft_Classification

I started this project after having one thought. Wouldn't it be cool to take a picture of an airplane with a smartphone and it tells you what kind of plane it is?

This is a massive project that may take years to perfect it, and I chip it away little by little, simply because:  
1. Airplanes look very very similar to one another
2. User should be able to take the photo from any (reasonable) angle.
3. Different planes have different logos and paintings

To compensate, this project needs massive data set. Although I managed to gather at over 10,000 pictures, that is simply not enough.

As a small step forward, I completed a neural network model that distinguishes Boeing 737 and Boeing 747. They are particularily easy to distinguish because b747's fuselage increases in thickness for about half its length as shown below.

B 737 | B 747
----------- | ------------
![b 737](https://github.com/Davidnh8/Aircraft_Classification/blob/master/b737.jpg) | ![b 747](https://github.com/Davidnh8/Aircraft_Classification/blob/master/b747.jpg)

The result of B 737 vs B 747 classification can be found in [Aircraft_Classification.ipynb*](https://github.com/Davidnh8/Aircraft_Classification/blob/master/Aircraft_Classification.ipynb). Overall the model performs reasonably, but it is slightly overfit. Also I believe the test set and training set share images, and I am in the process of methodotically identifying the intersections.

The end goal, of course, is to generalize it to all aircrafts.

* Note that occasionally, github has trouble loading the ipython notebook.
