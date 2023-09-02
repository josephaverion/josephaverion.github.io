---
layout: project
type: project
image: img/sort-visualizer/sorting-visualizer.png
title: "Sorting Algorithms Visualizer"
date: 2022
published: true
labels:
  - Java
  - Swing
  - Algorithms
summary: "Built a GUI desktop application to visualize popular sorting algorithms"
---
I implemented a sorting visualizer using Java and the Swing framework for the GUI. Currently, Insertion Sort, Selection Sort, Bubble Sort, Heap Sort, Merge Sort, and Quick Sort can be visualized in this application.

By clicking the start button the user shuffles an array length of a value the user chooses with a slider and is sorted using an algorithm they choose from a dropdown list. Also, the user can choose how fast the algorithm runs with a slider. While the algorithm runs, the user can see the array bars being sorted where the height of the bar represents a value in an array of numbers, and the speed/size modifiers are disabled. The user can reset the array and stop the algorithm using the stop button.

Here is a quick showcase of one of the sorting algorithms, quick sort.

![Quick Sort](/img/sort-visualizer/quick-sort-showcase.gif)

[Features and other sorts are shown here](https://www.youtube.com/watch?v=bZ7tsf0GHfA&ab_channel=JosephCarmeloAverion)

After doing this project, all these sorting algorithms stuck with me even more, especially the O(nlogn) sorts because I never tried coding them before. Also, if I ever need a refresher I can just open up this app. In the future, I hope to implement other sorting algorithms in this program.

[Source Code](https://github.com/josephaverion/SortingVisualizer/tree/master/SortingVisualizer/src)
