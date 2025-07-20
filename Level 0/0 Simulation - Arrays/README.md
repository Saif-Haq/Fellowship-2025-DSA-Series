## 📚 List of Problems

1. [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/description/) ✅ 
2. [Find the Highest Altitude](https://leetcode.com/problems/find-the-highest-altitude/)  ✅ 
3. [Final Value of Variable After Performing Operations](https://leetcode.com/problems/final-value-of-variable-after-performing-operations/description/) ✅ 
4. [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/description/)   ✅ 
5. [Concatenation of Array](https://leetcode.com/problems/concatenation-of-array/)  ✅ ✅ 
6. [Number of Good Pairs](https://leetcode.com/problems/number-of-good-pairs/description/)  
7. [Shuffle the Array](https://leetcode.com/problems/shuffle-the-array/description/)  
8. [Move Zeroes](https://leetcode.com/problems/move-zeroes/description/)  
9. [Maximum Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/)
10. [Left Rotate an array by one place](https://leetcode.com/problems/rotate-array/)

---

## 💡 Suggestions

- Make sure to prepare your notes alongside solving each problem.  
- Don’t spend more than 30–40 minutes on a single problem.  
- If you’re stuck on a problem, search on YouTube using the problem number.  
- Try to solve a problem in multiple ways.



Notes
(1)

Used a nested loop to calculate the sum from scratch for each index.
Was not accumulating the sum inside the inner loop.

Misusing push with brackets: output.push[s].

Improved Version (O(n) approach):
You correctly introduced a variable lastsum to carry the previously computed sum.
You pushed the new sum into the result array — ✔️ nice.
But you forgot to update lastsum, so the same value kept being added repeatedly.

Final Fix:
Realized you needed to do: lastsum = newSum; after pushing the value.
With that one line, your logic became fully correct and efficient.
