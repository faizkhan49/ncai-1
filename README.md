#### Running the project

* Download Tesseract for you OS
* Change or delete ***os.environ['TESSDATA_PREFIX']*** in the **main.py**
* Run the **main.py**

#### Steps:
Currently 3 steps are provided:
* Detecting symbols position (bounding boxes) using Tesseract
* Grouping bounding boxes into line/row
* Creating one bounding box for each line (by combining the bounding boxes in each group)

## The task:
* Choose the results from any of the previous steps
* Find and choose any error in the result, it can be 
  - any missed symbol/number by Tesseract
  - the incorrect boxes' grouped
  - incorrect lines boxes (one line contain another, or have big intersections, or one line box contains text from different lines)
* Make a solution of any chosen problem

#### Additionally
If you can't realize all of your ideas during the couple of hours, just write down all of your ideas.
The ideas can be connected not only with the chosen problems, but with the project at all.