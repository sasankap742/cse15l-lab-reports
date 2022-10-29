PART 1:
Codeblock of SearchEngine

![image](https://user-images.githubusercontent.com/78668680/198790564-dae272c1-74d3-4d8b-8415-a55bed929408.png)
![image](https://user-images.githubusercontent.com/78668680/198790707-23d0ec79-558e-427c-a610-450b2c8c1ecf.png)

Run server and SearchEngine

![image](https://user-images.githubusercontent.com/78668680/198790974-d119355f-9229-4109-912a-0e58458a07ee.png)


URL

![image](https://user-images.githubusercontent.com/78668680/198791109-5575ee2c-2d65-4b8e-94b9-2e9628e82bb8.png)

When I first visit the path without any arguments, it doesn’t enter any of the if statementsin the SearchEngineHandler.
It simply returns the default return statement which tells about /add and /search.

![image](https://user-images.githubusercontent.com/78668680/198791256-e2883609-baaf-4636-9f6e-e58871708cd4.png)

Calling query /add with an argument after = , makes sure that argument is added to the list that keeps the strings stored. 
The relevant argument given here in this example is “apple”. The method adds this argument to the list.

![image](https://user-images.githubusercontent.com/78668680/198791746-28feefe1-a43d-4924-841a-635ba85638f7.png)

If this value changes, it means that you are providing a different argument. 
So, it will also be added to the list without affecting the previously added Strings.
In this example, I am adding “pineapple” instead of “apple”. The previously added “apple” is still in the list when the method adds this to the list.


PART 2:

Example 1:
The failure-inducing input 

![image](https://user-images.githubusercontent.com/78668680/198792495-1bbe01d3-4d87-40d9-a6bb-969ca2d9e9a3.png)


The symptom

![image](https://user-images.githubusercontent.com/78668680/198792576-aa07e0ae-5a28-48ba-81a7-7575e5747c30.png)


Bug

![image](https://user-images.githubusercontent.com/78668680/198792785-221c1135-899c-46f1-be4a-968ab73a776b.png)

Code fix

![image](https://user-images.githubusercontent.com/78668680/198792899-8594c39b-94dc-4a27-bd58-e26408035d6e.png)


The bug causes this symptom( the item at index 0 is 0 not 4) because the bug is essentially copying elements from the newArray onto arr[]. 
The element at index 0 is 0 at the end because the newArray’s elements were all 0s as it was just created without any given values. 

Example 2:
The failure-inducing input 

![image](https://user-images.githubusercontent.com/78668680/198793135-d52029c6-0138-441f-b692-1e3176ea5794.png)

The symptom

![image](https://user-images.githubusercontent.com/78668680/198793238-7d7455a6-48d5-46c2-8a90-f0dfe091ede3.png)

Bug

![image](https://user-images.githubusercontent.com/78668680/198793346-c30f97df-5ee3-460b-a8d5-2d2941e8ae21.png)

The bug here is that there is no recursive function to call within more directories. So it does not visit the files within more-files. 
That’s why the symptom was returning the more-files directory instead of the two files within the more-files directory.
