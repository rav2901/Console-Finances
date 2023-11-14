# Console-Finances
Week 4 challenge javascript
The task is to create a code for analyzing the financial records of a company. A financial dataset is provided, it is
composed of arrays with two fields, Date and Profit/Losses.
The task got difficult once I had to find the average of the **changes** in Profit/Losses over the entire period.
I first tracked the changes from month to month - substract. I stored those values in a new array so that I can calculate the average.
I've used for loops and the .push method.
A a beginner, I've spent many hours to figure out how to get the correct result.

https://stackoverflow.com/questions/19302863/issue-of-comparing-element-in-array-to-previous-one-and-not-going-out-of-bounds

//https://blog.hubspot.com/website/javascript-array-push#:~:text=an%20existing%20array.-,The%20.,multiple%20elements%20to%20an%20array.

Finally, I had to find the greatest increase and greatest decrease in profi/ losses:
I've used  for if, the new array I made (to find the amounts) and the original array finances (to find the months).
![Capture for readme](https://github.com/rav2901/Console-Finances/assets/98492291/a23b50e8-d004-434e-96e9-578880236aed)
