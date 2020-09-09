# LeetCode - Integer to Roman

Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.

| Symbol  | Value  |
|---|---|
|  I | 1  |
|  V |  5 |
|  X | 10  |
|  L | 50  |
|  C | 100  |
|  D | 500  |
|  M | 1000  |

Given an integer, convert it to a roman numeral. Input is guaranteed to be within the range from 1 to 3999.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not IIII. Instead, the number four is written as IV. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as IX. There are six instances where subtraction is used:

    I can be placed before V (5) and X (10) to make 4 and 9. 
    X can be placed before L (50) and C (100) to make 40 and 90. 
    C can be placed before D (500) and M (1000) to make 400 and 900.

Here are some examples:

**Example 1:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Input:* 3

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Output:* "III"

**Example 2:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Input:* 4

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Output:* "IV"

**Example 3:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Input:* 9

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Output:* "IX"

**Example 4:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Input:* 58

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Output:* "LVIII"

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Explanation:* L = 50, V = 5, III = 3.

**Example 5:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Input:* 1994

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Output:* "MCMXCIV"

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Explanation:* M = 1000, CM = 900, XC = 90 and IV = 4.
