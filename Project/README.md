#Project
To run the program go to this link https://hub.gke.mybinder.org/user/95kevingarcia-d-ng-finalproject-nn7rcf2o/lab
There the main.ipynb is the file that you want to run. Under the Kernel tab click restart Kernal and run all cells. 
If the program says something about the kernel being unresponsive, delete 80 books from the Books folder to get to 20 books total.
Then change "50" in lines 536 537 539 and 540 to 10. This is a bug where the online binder cannot run through all of the books before it thinks it is unresponsive.
However if you run the code through a docker set up on your on computer then it will run. The program takes a while to initialize all of the data as it reads the books in their raw format.
