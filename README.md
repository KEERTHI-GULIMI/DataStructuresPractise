# DataStructuresPractise

I always get confused when to to use sliding window and when to use map while solving problems,
even after knowing that sliding window is used to move window and map to store frequencies.
So, two pointer method can be used 
A contiguous subarray (i.e., a portion of the array that is continuous, such as [arr[i], arr[i+1], ..., arr[j]]).
Constraints on the size or sum of the subarray (e.g., fixed-length subarray, maximum/minimum sum, or sum within a certain range).
The window size can change dynamically based on certain conditions (e.g., growing and shrinking).
You need to count occurrences of elements, or track frequency of certain values.
You need to store previously seen values and quickly check if they have appeared before.
You want to avoid nested loops and use the hashmap to optimize a brute force solution to linear time.
You need to handle cases where the subarrays do not necessarily have to be contiguous.
You are dealing with sums, differences, or prefixes (like in prefix sums or cumulative sums).
