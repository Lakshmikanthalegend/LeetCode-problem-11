# LeetCode-problem-11
Container with most Water

The "Container With Most Water" problem is solved efficiently using the two-pointer technique. I initialize two pointers, one at the beginning and the other at the end of the height array. The area between the lines is determined by the shorter height and the distance between the pointers. I calculate the area and update the maximum area found. Then, I move the pointer with the shorter height inward to explore potentially larger areas. This approach ensures I check all possible containers while minimizing time complexity to O(n), making it optimal for large inputs.
