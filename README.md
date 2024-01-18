# Sorting Visualizer

[Download](https://github.com/dipesh-m/Sorting-Visualizer/releases/tag/1.0)

Visualizing Various Sorting Algorithms in C++ Using the SDL2 Library.

A sorting algorithm is a procedure that organizes the elements of a list in a specific order. Although numerous sorting algorithms exist, practical implementations often emphasize a select few. In this sorting visualizer implementation, we will explore several sorting algorithms and gain a visual understanding of their operations.

The covered sorting algorithms include Selection Sort, Insertion Sort, Bubble Sort, Merge Sort, Quick Sort, and Heap Sort. The list size is set at 130 elements, offering the option to randomize the list and choose any sorting algorithm from the provided selection. It's important to note that all sorting algorithms in this visualization arrange elements in ascending order.

While the visualized sorting time for each algorithm doesn't precisely reflect their actual time complexities, adjustments have been made for relative clarity. Faster algorithms like Merge Sort have intentionally been slowed down to ensure proper visualization.

# How to run:-

Option 1.) You can run Sorting Visualizer directly from the release. Download the release and run the .exe application i.e., Sorting Visualizer.exe -> [Download](https://github.com/dipesh-m/Sorting-Visualizer/releases/tag/1.0)

Option 2.) You can also run Sorting Visualizer using the C++ source code available in the repository i.e., Sorting Visualizer.cpp but you will need to install and setup the SDL2 library first. I recommend you follow Lazy Foo' Productions' tutorial to setup SDL2 Library. PLEASE NOTE THAT the tutorial follows to setup SDL2 32-bit library but to run Sorting Visualizer, you have to use the 64-bit library. Just use x86_64-w64-mingw32 folder instead of i686-w64-mingw32 to setup the SDL2 files.-> [How to download and setup SDL2 library](http://lazyfoo.net/tutorials/SDL/01_hello_SDL/index.php).
After setting up the SDL2 library, just include the Sorting Visualizer.cpp file from the repository in your project with the build options as mentioned in the tutorial and build and run the project.

# Controls:-

WARNING: Giving repetitive commands may cause latency and the visualizer may behave unexpectedly. Please give a new command only after the current command's execution is done.

Available Controls inside Sorting Visualizer:-
- Use 0 to Generate a different randomized list.
- Use 1 to start Selection Sort Algorithm.
- Use 2 to start Insertion Sort Algorithm.
- Use 3 to start Bubble Sort Algorithm.
- Use 4 to start Merge Sort Algorithm.
- Use 5 to start Quick Sort Algorithm.
- Use 6 to start Heap Sort Algorithm.
- Use q to exit out of Sorting Visualizer

# Samples

- Sample 1 (Insertion Sort)

![](samples/example1.gif)


- Sample 2 (Merge Sort)

![](samples/example2.gif)
