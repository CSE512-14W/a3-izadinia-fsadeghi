a3-izadinia-fsadeghi
===============

## Team Members

1. Hamid Izadinia izadinia@uw.edu
2. Fereshteh Sadeghi fsadeghi@uw.edu

## Project Name

In this project we want to show the relationship between the occurrence of different object, attributes in different scenes in an image set. The recognition of these components are fundamental problems in computer vision community. The learning of detectors for each of these three components usually involve the joint relationship between them. For example for learning the detectors for "dining room" class we can use the detector of the objects which are appearing in "dining room" scene to improve the detection of scene class. On the other hand, recognition of each smaller components such as individual object can improve using the accurate recognition of scene type for the image.


## Running Instructions

This is a web-based visualization project and can be opened online at (http://cse512-14w.github.io/a3-izadinia-fsadeghi/). 
** [IMPORTANT] The project looks much nicer in chrome with full screen mode. After you made it full screen then refresh it again. **

Using this link you will open index.html file and run the visualization. We use bundle layout in D3 to show the link between different nominal variables. Here we have three types of variables: 

1) Scene: dining room, mountain, ...
2) Object: chair, table, ...
3) Attribute: indoor, outdoor, natural, ...

The link between each variable show the concurrence of those variables in the image set. Since there are many variables in the graph, you can search for specific string in the search box on top of the page. The variables with similar pattern will get highlighted and then by moving mouse over the variable of interest, the link of that variable with other variables get highlighted. Then by clicking on the text of that variable a popup will open and show the thumbnail of a sample image for each category. 


## Story Board

The storyboard of the project can be opened by [link to the storyboard pdf file](storyboard.pdf?raw=true).

![inital storyboard](parallel.png "Inital storyboard")

### Changes between Storyboard and the Final Implementation

The changes between Storyboard and final implementation is explained in [link to the storyboard pdf file](storyboard.pdf?raw=true).


## Development Process

The workload of the project is divided in every step. The details are as follows:

- discuss about the dataset and rough sketch of interactive visualization in first stages. (Fereshteh Sadeghi: 4 hrs, Hamid Izadinia: 4 hrs)
- getting familiar with html,css,d3 by reading TA materials (Fereshteh Sadeghi: 5 hrs, Hamid Izadinia: 5 hrs)
- reading tutorials and seeing the d3 visualization examples in web (Fereshteh Sadeghi: 9 hrs, Hamid Izadinia: 8 hrs)
- making data ready for visualization including computing the statistics from the dataset, finding the important elements and converting the data format to JSON which is d3 friendly. (Fereshteh Sadeghi: 15 hrs, Hamid Izadinia: 3 hrs)
- implementing our visualization and playing with different styles such that the visualization interface looks better. (Fereshteh Sadeghi: 9 hrs, Hamid Izadinia: 22 hrs)
