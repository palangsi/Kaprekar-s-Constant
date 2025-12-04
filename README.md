 The process of reducing a 4-digit number to **6174** is known as **Kaprekar's Routine**, named after the Indian mathematician D. R. Kaprekar. It's an elegant demonstration of how simple arithmetic operations can lead to a fixed, fascinating result.

Here is the step-by-step explanation of the routine:

### The Kaprekar Routine (The $6174$ Reduction)

The routine is guaranteed to work for **any 4-digit number** (from $1000$ to $9999$), with the single exception of numbers where all four digits are identical (like $1111$, $5555$, or $9999$).

#### **Step 1: Choose Your Starting Number**

Pick any 4-digit number where at least two of the digits are different.

* **Example:** Let's choose the number $\mathbf{3524}$.

#### **Step 2: Form the Largest and Smallest Numbers**

Using the four digits of your current number, rearrange them to create two new numbers:
1.  **The Largest Number (Descending Order):** Arrange the digits from highest to lowest.
2.  **The Smallest Number (Ascending Order):** Arrange the digits from lowest to highest.
    * **Crucial Rule:** If your number has fewer than four unique digits, you **must use leading zeros** to keep the smallest number 4 digits long.

* **Example (Starting from 3524):**
    * Largest (Descending): $\mathbf{5432}$
    * Smallest (Ascending): $\mathbf{2345}$

#### **Step 3: Perform the Subtraction**

Subtract the smallest number from the largest number. This result is your new number.

* **Example (Starting from 3524):**
    $$5432 - 2345 = \mathbf{3087}$$

#### **Step 4: Repeat the Process**

Take the result from Step 3 and use it as your new starting number. Return to Step 2 and repeat the rearrangement and subtraction process.

* **Example (Continuing with 3087):**
    * Largest (Descending): $\mathbf{8730}$
    * Smallest (Ascending): $\mathbf{0378}$ (Note the leading zero!)
    * Subtract: $8730 - 0378 = \mathbf{8352}$

#### **Step 5: The Fixed Point**

Continue repeating the routine until you reach the number **6174**. This will happen in a maximum of seven steps.

* **Example (Continuing with 8352):**
    * Largest: $\mathbf{8532}$
    * Smallest: $\mathbf{2358}$
    * Subtract: $8532 - 2358 = \mathbf{6174}$

Once you reach $6174$, the routine stops because the number is a **fixed point**. If you repeat the process with 6174:

* Largest: $\mathbf{7641}$
* Smallest: $\mathbf{1467}$
* Subtract: $7641 - 1467 = \mathbf{6174}$ (It remains $6174$).

This simple, self-perpetuating process is what makes **6174** Kaprekar's Constant. 
