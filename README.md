
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Math calculations reference sheet</title>
        <style>
        
        html {
            background-color: rgb(5, 213, 255);
        }
        
        h1 {
            background-color: rgb(64, 33, 219);
            color: orange;
        }
        
        h2 {
            background-color: red;
            color: white;
        }
        
        a {
            background-color: orange;
            color: rgb(43, 10, 255);
        }
        
        p {
            background-color: black;
            color: white;
        }
        
        strong {
            color: yellow;
        }
        
        .formula {
            font-size: 24px;
            color: red;
        }
        
        .formula-stuffing {
            font-size: 22px;
            color: rgb(227, 16, 227);
        }
        </style>
    </head>
    <body>
        <h1>Math Calulations Reference Sheet</h1>
            <h2 id = "top">Table of contents</h2>
                <ol>
                    <li><a href = "#mean">Mean</a></li>
                    <li><a href = "#median">Median</a></li>
                    <li><a href = "#mode">Mode</a></li>
                    <li><a href = "#range">Range</a></li>
                    <li><a href = "#IQR">Interquartile Range                     </a></li>
                    <li><a href = "#MAD">Mean Absolute                          Deviation</a></li>
                    <li><a href = "#what-outliers">What are                     outliers?</a></li>
                    <li><a href = "#outliers">How to find                       outliers</a></li>
                </ol>
            <h2 id = "mean">1. Mean</h2>
                <p> 
                    To find the mean of any data set, the first thing that you have to do is you have to <strong>find the sum of all of the numbers in the data set.</strong> Yes, this can be a pain in the butt, but you have to do it if want to or have to find the mean. I will use the data set of 80, 85, 96, 98, 99, 105, and 85. The sum of all of these numbers is 648. <strong>Now, you have to divide this number by the amount of numbers in the data set.</strong> So, in this case, you have to divide 648 by 7, that is approximately 92.6. That right there is your mean. <strong>What you are finding here is the average of the numbers in the data set. What you are doing here, is you are taking all of the numbers, and then evenly redistributing them.</strong><br>

<em class = "formula">Formula:</em> 
<em class = "formula-stuffing">Mean = (80+85+96+98+99+105+85 )/ 7<br>
648/7<br>
~ 92.6
</em><br>

<a href = "#top"><em>Back to the top</em> </a>                               </p>
            
            <h2 id ="median">2. Median</h2>
                <p>
                To find the median of any data set, the first step is to <strong>arrange the numbers from least to greatest.</strong> I will use the same data set I used in the explanation for the mean. The numbers were 80, 85, 96, 98, 99, 105, and 85. If you arrange them from least to greatest, then they would look like this. 80, 85, 85, 96, 98, 99, 105. <strong>Now, you have to find the middle number of all of these numbers. The middle number will be the one which has equal numbers on either side of it.</strong> In this case it will be the number 96. <strong>There is also another part to this.</strong> I will use the data set 1, 2, 3, 4. Now there is no middle number. For this, you <strong>will have to find the mean of the middle two numbers.</strong> The mean of the middle two numbers is 5/2 which is 2.5. That is your median.<br>

<em class = "formula">Formula:</em>
<em class = "formula-stuffing">80, 85, 96, 98, 99, 105, 85<br>
80, 85, 85, 96, 98, 99, 105<br>
96 is the median<br><br>

1, 2, 3, 4<br>
Median = (2+3)/2<br>
= 5/2<br>
= 2.5<br>
2.5 is the median<br>
</em>

<a href ="#top"><em>Back to top</em></a>
                </p>
                
            <h2 id = "mode">3. Mode</h2>
                <p>
                To find the mode, <strong>the first step is to find which numbers repeat.</strong> I will use the data set 80, 85, 96, 98, 99, 105, and 85. The number that repeats the most is 85. That is your mode. <strong>This is not the only case that can come up when calculating a mode</strong>. If I take the data set 1, 1, 2, 2, <strong>then there are two numbers that are repeating the same number of times. They are both the mode</strong>. So, the modes of this data set are 1 and 2. <strong>The mode is the number that repeats the most in the data set. If a number repeats the same number of times as another number, they are both modes.</strong> This will not usually come in handy for real life situtations. It is also very simple to calculate.<br>

<em class = "formula">Formula: </em>
<em class = "formula-stuffing">
80, 85, 96, 98, 99, 105, 85<br>
= 85 comes up two times<br>
Therefore, the mode is 85<br><br>

1, 1, 2, 2<br>
= 1 comes up twice and 2 comes up twice<br>
Therefore the modes are 1 and 2<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
            <h2 id = "range">4. Range</h2>
                <p>
                To find the range, the first step is <strong>to find the highest number and the lowest number in the data set.</strong> Again, I will use the data set 80, 85, 96, 98, 99, 105, and 85. We can identify that the greatest number in the data set is 105. The lowest valued number in the data set is 80. The second step to finding the range is <strong>to find the difference between the greatest and least numbers in the data set.</strong> This would mean that we subtract 105 by 80. We get 25. That is our range. What we are doing here is we are finding by how much the data in the data set varies.<br>
<em class = "formula">Formula:</em>
<em class = "formula-stuffing">80, 85, 96, 98, 99, 105, 85<br>
Least number: 80<br>
Greatest number: 105<br>
Difference formula: 105-80<br>
Difference: 25<br>
Therefore, the range is 25.<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
            <h2 id = "IQR">5. Interquartile Range/IQR</h2>
                <p>
                To find the IQR of any data set, the first step is to <strong>find the median of the data set.</strong> In the data set 80, 85, 96, 98, 99, 105, 85, the median is 96. That is your <strong>second quartile.</strong> Your <strong>first quartile</strong> is the first half of the data set without the median. The first quartile in this data set is 80, 85, 85. The <strong>third quartile</strong> is the third quartile is the second half of the data. In this case, the third quartile is 98, 99, and 105. The second step to finding the IQR of any data set is to <strong>find the medians of the first and third quartiles.</strong> The median of first quartile is 85. The median of the second quartile is 99, The third and final step to finding the <strong>IQR</strong> of any data set is to <strong>find the difference between the medians of the first and third quartiles.</strong> The difference between 99 and 85 is 14. That is your IQR. Another case that could come up is that you could have an even number of numbers in the data set. My data set is 1, 2, 3, 4. There is no median, so we have to find the mean of 2 and 3. That is 2.5. That is the median. To find the quartiles, we keep the all of the numbers. The first quartile would be 1, and 2. The third quartile would be 3, and 4. The median of the first quartile is 1.5 and the median of the third quartile is 2.5. The difference between the two is 1. <strong>What we are finding here is we are finding the range between each of the numbers in the data set.</strong> The range between each of the numbers in the data set is no more than 1.<br>
<em class = "formula">Formula:</em>
<em class = "formula-stuffing">80, 85, 85, 96, 98, 99, 105<br>
Median: 96<br>
New data set: 80, 85, 85, 98, 99, 105<br>
First Quartile: 80, 85, 85<br>
Third Quartile: 98, 99, 105<br>
Median of First Quartile: 85<br>
Median of Third Quartile: 99<br>
Difference between medians: 99-85 = 14<br>
IQR: 14<br><br>

Data set: 1, 2, 3 ,4<br>
Median: 2.5<br>
New data set: 1, 2, 3, 4<br>
First Quartile: 1, 2<br>
Third Quartile: 3, 4<br>
Median of Fist Quartile: 1.5<br>
Median of Third Quartile: 2.5<br>
Difference between medians: 2.5-1.5 = 1<br>
IQR: 1<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
            <h2 id = "MAD">6. Mean Absolute Deviation/MAD              </h2>
                <p>
                    To find the <strong>MAD</strong> of any data set, the first step is to <strong>find the mean of the data set.</strong> The mean for the data set 80, 85, 96, 98, 99, 105, 85 is about 93. The second step to finding the MAD is to <strong>Take the difference of evry number in the difference of every number in the data set by 93, the mean.</strong> The new data set would be 13, 8, 3, 5, 6, 12, and 8. The third step <strong>is to find the mean of all of these new numbers.</strong> That would be 55/7. That is about 7.86. That is your MAD. What you are finding here is you are finding the average deviation from the mean. If the MAD is close to 0, that means that your numbers are all very close to their mean.<br>
<em class = "formula">Formula:</em>
<em class = "formula-stuffing">80, 85, 85, 96, 98, 99, 105<br>
Mean ~ 93<br>
Take the difference of all of the numbers by 93<br>
New data set: 13, 8, 3, 5, 6, 12<br>
Mean of new data set: 7.86<br>
MAD: 7.86<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
            <h2 id = "what-outliers">7. What are outliers?</h2>
                <p>
                What exactly are <strong>outliers?</strong> That has a simple answer to it. Just they are the numbers that are much greater or much lower than the all of the other numbers in the data set. You might be thinking that none of the other values that we have learned about have anything to do with this, but yes, they do. <strong>IQR</strong> especially has a big role in this. Most importantly, outliers can <strong>compeletely change some of the measures of center.</strong> If there was a data set like 1, 2, 3, 10, then we know that ten is the outlier because it is much greater than any of the other numbers. That was easy, but it will get harder. But what you really need to know right now is how much difference it can do. With the outlier, the range is 2. With the outlier the range is 9. Without the outlier, the mean is 2. With the outlier, the mean is 4. This is what outliers can do. Find out <strong>how to find outliers</strong> in the next section.<br>
<em class = "formula">Formula:</em>
<em class = "formula-stuffing">Data set: 1, 2, 3, 10<br>
Mean without outlier: 2<br>
Mean with outlier: 4<br><br>

Range without outlier: 2<br>
Range with outlier: 9<br><br>

IQR without outlier: 2<br>
IQR with outlier: 5<br><br>

MAD without outlier: 2/3<br>
MAD with outlier: 3<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
            <h2 id = "outliers">8. How to find outliers</h2>
                <p>
                In the last part, you learned <strong>what are outliers.</strong> You learned that outliers are numbers that are much, much greater, or much, much lower than all of the numbers in the data set. In the <strong>formula section</strong>, you experienced how badly the outliers can affect the measures of center and variation. But what do we do when one number looks like a outlier, but we are not sure? Yes, we use a calculation! To find the outlier in any data set, <strong>we have to first find the IQR of the data set.</strong> We will use the data set 80, 85, 96, 98, 99, 105, and 85. The <strong>IQR</strong> of the data set is 14. <strong>The second step to finding the outlier of any data set's first quartile is to use this equation: Q1-1.5(IQR)</strong> Anything less than that is an outlier. If we substitute, then this our new equation. 85-1.5(14). This is 64. Anything that is less than 64 is an outlier. To find the outlier for the thrid quartile, use this equation: <strong>Q3+1.5(IQR)</strong>. This is our new equation if we substitute: 99+1.5(14). This is 120. Anything that is greater than 120 is an outlier.<br>
<em class = "formula">Formula:</em>
<em class = "formula-stuffing">Data set: 80, 85, 85, 96, 98, 99, 105<br>
IQR of data set: 14<br>
Equation to find outliers of first quartile: Q1-1.5(IQR)<br>
= 85-1.5(14)<br>
= 85- 21<br>
= 64<br>
Therefore any number lower than 64 is an outlier.<br><br>

Equation to find out outliers of third quartile: Q3+1.5(14)<br>
= 99+1.5(14)<br>
= 99+21<br>
= 120<br>
Therefore, any number greater than 120 is an outlier.<br><br>

This means that any number that is greater than 120 or less than 64 is an outlier in this data set.<br>
</em>
<a href = "#top"><em>Back to top</em></a>
                </p>
    </body>
</html>
