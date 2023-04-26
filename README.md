# Linear_search
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.<br>
<br>
# How Linear Search Works?<br>
<b>*Step 1:</b> First, read the search element (Target element) in the array.<br>
<b>*Step 2:</b> Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.<br>
<b>*Step 3:</b> Match the key with arr[i].<br>
<b>*Step 4:</b> If the key matches, return the index. Otherwise, increment i by 1.<br>
<br>
# Illustration of Linear Search:<br>
Consider the array <b>arr[] = {10, 50, 30, 70, 80, 20, 90, 40} </b>and <b>key = 20</b><br>
<br>
<b>Step 1:</b> Set i = 0 and check key with arr[0].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234276829-9a85a8eb-4ca1-4be2-87b5-d6d266858646.png)
<br>
<b>Step 2:</b> key and arr[0] are not the same. So make i = 1 and match key with arr[1].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234276984-921ecd62-780e-4834-97cd-a1e9512e7005.png)
<br>
<b>Step 3: </b>arr[1] and key are different. Increment i and compare key with arr[2].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234277164-b629b19e-9f7f-4f3c-9f62-69ea14e938cf.png)
<br>
<b>Step 4:</b> arr[2] is not the same with key. Increment i and compare key with arr[3].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234277327-db88e8c3-6d9b-49ac-b036-d800adf0bac4.png)
<br>
<b>Step 5:</b> key and arr[3] are different. Make i = 4 and compare key with arr[4].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234277603-197ef17a-64df-4a3c-accd-19e305b35e0f.png)
<br>
<b>Step 6:</b> key and arr[4] are not same. Make i = 5 and match key with arr[5].<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234277743-c587f302-5e4d-4e49-8432-7bdb0e7db17c.png)
<br>
<br>
<b><ins>Time Complexity:</b></ins><br>
<br>

<ol><b>Best Case:</b></ol> In the best case, the key might be present at the first index. So the best case complexity is O(1)<br>
<br>
<ol><b>Worst Case:</b></ol> In the worst case, the key might be present at the last index i.e., opposite to the end from which the search has started in the list. So the worst case complexity is O(N) where N is the size of the list.<br>
<br>
<ol><b>Average Case:</b></ol> O(N)<br>
<br>
<b><ins>Auxiliary Space:</b></ins> O(1) as except the variable to iterate through the list, no other variable is used.<br>
<br>
<br>
<b><ins> Output</b></ins>
<br>
<img width="923" alt="Linear Search" src="https://user-images.githubusercontent.com/125802204/234279491-b761f2ea-904a-4123-b9e0-bf5722853cf4.png">
