# :alien: Assignment 1 - Help John with Parallel Programming! :fire::dancer:

In this assignment we are helping a random person John. John is a data engineer who works at Lola Inc. He wants to download some pictures from internet, and resize them, however, his process takes a lot of time as the number of images increases. He asks your help, to speed up his process.

## The Goal

The goal is to achieve concurrent programming using Python. This project i have done the two ways of parallelising tasks, in which i improve the speed of the serial-programming application by using threading and/ or multiprocessing.

Things to remember, 

1. IO bound operations requires threading
2. CPU bound operations requires multiprocessing

There are many options for multithreading and multiprocessing. You are more than welcome to choose any of those libraries including the standard packages.
But i am using this kindd of Library

- [multiprocessing](https://docs.python.org/3.8/library/multiprocessing.html)
- [threading](https://docs.python.org/3.8/library/threading.html)

In task one, gathering the images from Imgur, the library “concurrent.future” was used.And In task two, resizing the images, the library “multiprocessing” was used.

I can says that its really improve the speed of the serial-programming application by using threading and/ or multiprocessing.
