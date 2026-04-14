Q1: Digit Gatekeeper
Approach:
1. Iterative Search: The program iterates through every integer i from the lower limit L to the upper limit R.
2. Filtering: For each number, it checks if the number is divisible by K and if the digit sum of i is a prime number (while ensuring the number contains no zeros).
3. Prime Checking: The is_prime function uses trial division up to the square root of the sum to check for primality.
Complexity:
- Time Complexity: O(N * log R), where N is the range (R - L). The log R factor accounts for digit extraction and the small, constant-time primality test on the digit sum.
- Space Complexity: O(1).

Q2: Roll Seed Lock
Approach:
1. Transformation Loop: The input Num undergoes three specific mathematical transformations based on whether the current value is even or odd, incorporating the seed value.
2. Validation: It checks if the final result is a 3-digit integer (100-999).
3. Digit Matching: It checks if the middle digit of the final number matches the original seed.
Complexity:
- Time Complexity: O(1) because the loop runs for a fixed 3 iterations regardless of input size.
- Space Complexity: O(1).

Q3: Mirror Corridor
Approach:
1. Brute Force Search: The code checks integers X starting from 0 up to 100,000.
2. Conditions: For each X, it calculates S = N + X and checks if S is divisible by K and if S is a palindrome.
3. Palindrome Check: It converts the sum to a string and compares characters from both ends.
Complexity:
- Time Complexity: O(M * log S), where M is the iteration limit (100,001) and log S represents the number of digits in the sum.
- Space Complexity: O(log S) for the string representation of the sum.

Q4: Fare Calculator
Approach:
1. Base Calculation: Calculates a fare using the formula base + 7 * distance.
2. Surcharges: Adds a flat fee if late by more than 15 minutes and a 10% tax if distance is over 10.
3. Seed Adjustment: Adds or subtracts the seed value based on whether the seed is even or odd.
4. Rounding: Rounds the final total up to the nearest multiple of 5.
Complexity:
- Time Complexity: O(1).
- Space Complexity: O(1).

Q5: Skipping Numbers
Approach:
1. Accumulation: The program increments a counter m and adds it to a total sum until the sum reaches or exceeds Num.
2. Skipping Logic: It skips adding m to the sum if m is a multiple of (seed + 2).
Complexity:
- Time Complexity: O(sqrt(Num)). Since the sum grows quadratically relative to m, the number of steps to reach Num is proportional to the square root of Num.
- Space Complexity: O(1).

Q6: Contest Score Judge
Approach:
1. Score Calculation: Assigns 3 points for correct, 1 for partially correct, and -2 for wrong answers.
2. Penalty: Deducts 10 points if the total questions attempted (a+b+c) is greater than 50.
3. Threshold: Ensures the score is not negative and checks if it is at least 60 to pass.
Complexity:
- Time Complexity: O(1).
- Space Complexity: O(1).## Hi there 👋

<!--
**snigdha25-xx/snigdha25-xx** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
