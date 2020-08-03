# InterViewProblems
# Notes


	• Detect loop in linked list & detect one duplicate elements in array
		○ Sorting (Use merger sort for complexity )
		○ Hashing using unordered map
		○ Using another array of frequency , initialize to zero and then increment
		○ Using Floyd's tortoise algorithm {Slow and Fast pointer}
	
	• Sort array's of 0 , 1 and 2
		○ Simple sort
		○ Count sort
			§ Count the numbers and then print according the count
		○ Dutch National flag algorithm
			§ Low , mid , high three reference points.
		
	• Find missing and repeating number
		○ Sort (Array will be modified)
		○ Use frequency array (Array will not be modified)
		○ Calculate actual sum - total sum and same for square
			§ X2 - Y2 = sum2
			§ X-Y - sum1
			§ Calculate X and Y
		○ Using XOR and buckets
		
	• Find duplicates in array in O(1) space complexity
		○ Use double dabble method (OWN NAME)
		○ If(arr[arr[i]] >=0 )
			§ Scar[i]] = -1;
		○ Else
			§ Print arr[i] ;
	• Find first missing positive number
		○ Same double dabble method 
			§ Multiplying indexes of array elements  by -1
	• Merge two sorted arrays:
		○ Move all elements from both array to third one and then sort it (TC : O(N) + O(Nlog(N)) )
		○ Compare first element of both array and store it in third one (O(1) space complexity)
		
	• Maximum contiguous Subarrray sum :
		○ Brutforce solution N*3
		○ Optimize Brutforce to N*2
		○ Kadane's Algorithm 
			§ Use two variables sum = arr[0] and max 
			§ If(sum < 0)
				□ Sum = 0;
			§ Sum>max
				□ Max =sum
			§ https://www.geeksforgeeks.org/largest-sum-contiguous-subarray/
O(n) time complexity
