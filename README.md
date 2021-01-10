# Stock Analysis Using VBA
## Purpose
The goal for this project was to refactor existing code which analyses an entire dataset of stock the stock market for the years of 2017 and 2018 to determine which stock was worth investing with an optimal code.
## Results
When looking at the two years it is easy to see that the stock market in general weas doing better in 2017 com paired to 2018 as only stock had a negative return in 2017 compared to the ten stock that had negative returns. Looking at both years together, ENPH would have been the best stock to go after it had the biggest gains when both years are combined.

![image](https://user-images.githubusercontent.com/76131315/104133308-c30f9700-5350-11eb-83b8-2dcefc771823.png)

![image](https://user-images.githubusercontent.com/76131315/104133317-d1f64980-5350-11eb-98c0-ab6dd737f9ac.png)

When looking at the optimization of the code the refactored code was also much superior in terms of speed to run, as the refactored code ran in the 0.11 second range while the original code ran in the 0.67 range as seen below
### Original code

![image](https://user-images.githubusercontent.com/76131315/104133333-f0f4db80-5350-11eb-992f-501538c9ba65.png)

![image](https://user-images.githubusercontent.com/76131315/104133338-ffdb8e00-5350-11eb-9c1a-e230ceb42df1.png)

### Refactored code

![image](https://user-images.githubusercontent.com/76131315/104133354-1550b800-5351-11eb-9748-e66ecf229637.png)

![image](https://user-images.githubusercontent.com/76131315/104133359-1bdf2f80-5351-11eb-84a3-6b35fafa10e6.png)

At first glance the refactored code written out might seem more longer, but in truth the codes are almost the same size yet the refactored code has more comments to help if this code was to be viewed at a later time or by someone else and even if they are the same length, the refactored is more efficient as seen with the proof above.  
## Summary
To conclude, the best stock to invest in according to this data would be the ENPH stock, and in most cases, refactored code is more optimal as it allows for a faster processing time as well as either a cleaner or shorter code and/or one that is easier to follow as were the cases for this project. While there are plenty of advantages, the one major disadvantage is the time it would consume to refactor a long code, the original code in this case was already short but if the code is hundreds of pages long that it will take a long time to refactor it.
