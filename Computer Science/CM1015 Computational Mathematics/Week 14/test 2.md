### Exponential and logarithmic functions

##### 1. What is the value of 7^-4^

Select all the correct answers:

- ${\frac{1}{7 * 7^3}}$
- ${\frac{1}{4^7}}$
- 0.0004164931
- 0.0000610352

<details>
  <summary>Solution</summary>

  </br>

We want to evaluate:

\[
7^{-4}.
\]

1. **Rewrite \(7^{-4}\) using exponents:**
   By definition of negative exponents,
   \[
   7^{-4} = \frac{1}{7^4}.
   \]

2. **Check each option given:**

   - \(\displaystyle \frac{1}{7 \times 7^3}\)
     Since \(7^4 = 7 \times 7^3,\) it follows that
     \[
     \frac{1}{7 \times 7^3} = \frac{1}{7^4}.
     \]
     This **is** a correct representation of \(7^{-4}\).

   - \(\displaystyle \frac{1}{4^7}\)
     This would be \(\frac{1}{4^7} = \frac{1}{16384}\), which does **not** equal \(\tfrac{1}{2401}\). So this is **not** correct.

   - \(0.0004164931\)
     Numerically,
     \[
     \frac{1}{2401} \approx 0.0004164931 \quad(\text{to 10 decimal places}),
     \]
     which matches \(7^{-4}\). So this **is** a correct approximation.

   - \(0.0000610352\)
     This is approximately \(\tfrac{1}{16384}\), not \(\tfrac{1}{2401}\). So it is **not** correct.

---

Final Answer

The correct representations/values for \(7^{-4}\) among the options given are:

1. \(\displaystyle \frac{1}{7 \times 7^3}\) (exact form)
2. \(0.0004164931\) (approximate decimal form)

</details>

</br>

---

##### 2. The value of x, solve for the variable

3^x^ - 1 = 4

Select all the correct answers:

- x = 3
- x = ${\frac{log5}{log3}}$
- x = ${\frac{log3}{log5}}$
- x = ${\frac{1}{3}}$
- ≈ 1.46
- ≈ 0.68

<details>
  <summary>Solution</summary>

  </br>

We have the equation:

\[
3^x - 1 = 4.
\]

---

Step 1: Isolate the exponential term

\[
3^x = 4 + 1 = 5.
\]

---

Step 2: Solve for \(x\)

Rewrite in logarithmic form:

\[
x = \log_3(5).
\]

Using the change of base formula, this is equivalent to:

\[
x = \frac{\log(5)}{\log(3)},
\]

where \(\log\) can be \(\ln\) (natural log) or \(\log\_{10}\) (common log); the base doesn’t matter as long as it’s consistent.

---

Step 3: Approximate the value

Numerically:

\[
x \approx \frac{1.6094}{1.0986} \approx 1.4649 \approx 1.46.
\]

---

Step 4: Match with the given options

1. **\(x = 3\):**
   Substituting \(x=3\) would give \(3^3 - 1 = 27 - 1 = 26 \neq 4.\) Not correct.

2. **\(x = \tfrac{\log(5)}{\log(3)}\):**
   This is exactly the solution we found. **Correct.**

3. **\(x = \tfrac{\log(3)}{\log(5)}\):**
   This would be \(\log_5(3)\), which solves \(5^x=3\), not \(3^x=5.\) Not correct.

4. **\(x = \tfrac{1}{3}\):**
   Then \(3^{1/3} - 1 \approx 1.442 - 1 = 0.442 \neq 4.\) Not correct.

5. **\(x \approx 1.46\):**
   This matches our approximate calculation. **Correct.**

6. **\(x \approx 0.68\):**
   Not correct for \(3^x=5.\)

---

Final Answer

All correct solutions/values to the equation \(3^x - 1 = 4\) among the given options are:

1. \( \displaystyle x = \frac{\log(5)}{\log(3)}\)
2. \( x \approx 1.46.\)

</details>

</br>

---

##### 3. What is the value of x

0.5^x^ = 10

- x = ${\frac{log10}{log0.5}}$
- x ≈ -3.32
- x = ${\frac{10}{5}}$ = 2
- x = ${\frac{log0.5}{log10}}$
- x ≈ 0.3
- None of the other options is correct

<details>
  <summary>Solution</summary>

  </br>

We need to solve the equation:

\[
(0.5)^x = 10.
\]

---

1. Rewrite \(0.5\) in exponential form

Recall that \(0.5 = \tfrac{1}{2} = 2^{-1}\). So we have:

\[
(0.5)^x = (2^{-1})^x = 2^{-x}.
\]

Hence, the equation becomes:

\[
2^{-x} = 10.
\]

---

2. Solve using logarithms

Take the logarithm (let’s use \(\log\) base 10 for convenience) of both sides:

\[
\log\bigl(2^{-x}\bigr) = \log(10).
\]

Use the property \(\log(a^b) = b \,\log(a)\):

\[
-\,x \,\log(2) = \log(10).
\]

Thus,

\[
x = -\frac{\log(10)}{\log(2)}.
\]

But we also can write this in terms of \(0.5\), since \( \log(0.5) = \log\bigl(2^{-1}\bigr) = -\log(2)\). Hence,

\[
x = \frac{\log(10)}{\log(0.5)}.
\]

Given that \(\log*{10}(10) = 1\) and \(\log*{10}(0.5) \approx -0.3010\), numerically:

\[
x \approx \frac{1}{-0.3010} \approx -3.3219 \ (\text{rounded to } -3.32).
\]

---

3. Match with the provided options

- **\(x = \tfrac{\log(10)}{\log(0.5)}\)**
  This exactly matches our derived expression and is correct.

- **\(x \approx -3.32\)**
  This is the correct approximate decimal value.

- **\(x = \tfrac{10}{5} = 2\)**
  Not correct. Substituting \(x = 2\) yields \((0.5)^2 = 0.25 \neq 10\).

- **\(x = \tfrac{\log(0.5)}{\log(10)}\)**
  This would invert our correct fraction, which would solve \( (0.5)^{\frac{\log(0.5)}{\log(10)}} = 10\), but that’s not the same equation. Not correct.

- **\(x \approx 0.3\)**
  Substituting \(x = 0.3\) gives \((0.5)^{0.3} \approx 0.81\), definitely not 10. Not correct.

- **None of the other options is correct**
  We have already found correct matches above, so this is not the choice.

---

4. Final Answer

The correct solutions from the list are:

\[
x = \frac{\log(10)}{\log(0.5)}
\quad\text{and}\quad
x \approx -3.32.
\]

</details>

</br>

---

##### 4. Find x such that log~(x)~ = 4

Select all correct statements:

- None of other options is correct
- 4 = 2^2^ and hence log~2~(x) = 4 means x = 2
- x = 16
- x = 2

<details>
  <summary>Solution</summary>

  </br>

First, let's restate the problem clearly:

> **Problem**: Find the value of \(x\) that satisfies
> \[
> \log(x) = 4.
> \]
> Then, determine which of the given statements are correct.

The difficulty here is that the base of the logarithm \(\log(\cdot)\) is **not explicitly stated**. By convention in many contexts (particularly in high-school level algebra courses in certain regions), \(\log(x)\) often means \(\log*{10}(x)\). In higher mathematics or certain contexts, \(\log(x)\) might mean \(\ln(x)\) (log base \(e\)). Meanwhile, some textbooks or problems might use \(\log\) to mean \(\log*{2}\). Without a clear base, we have an ambiguity.

---

1. If \(\log\) means \(\log\_{10}\)

- The equation \(\log\_{10}(x) = 4\) means \(x = 10^4 = 10000\).
- Checking the provided options:

  1. None of the other options is correct
  2. \(4 = 2^2\) and hence \(\log\_{2}(x) = 4\) means \(x=2\)
  3. \(x = 16\)
  4. \(x = 2\)

  None of these is \(x = 10000\). Therefore, if the base is \(10\), the correct solution \(x=10000\) does **not** appear in the list. In that scenario, the only truthful statement would be

  > **"None of the other options is correct."**

---

2. If \(\log\) means \(\log\_{2}\)

- The equation \(\log\_{2}(x) = 4\) means \(x = 2^4 = 16\).
- Checking the same options with this interpretation:

  1. None of the other options is correct
  2. \(4 = 2^2\) and hence \(\log*{2}(x) = 4\) means \(x=2\) (This is **incorrect** reasoning; if \(\log*{2}(x)=4\), then \(x=16\), not 2.)
  3. \(x = 16\) (This is **correct** for \(\log\_{2}(x)=4\).)
  4. \(x = 2\) (Incorrect for \(\log\_{2}(x)=4\).)

  In this scenario, the correct statement is \(x = 16\), so statement #3 is true and statement #1 ("None of the other options is correct") would be false—because one of the other statements (\#3) _is_ correct.

---

3. Which Interpretation Is Most Likely?

- If a problem simply writes \(\log(x)\) without a base, the most common “default” in many high-school or standard algebra texts is \(\log\_{10}\). In that case, \(x = 10^4 = 10000\), and it matches **none** of the provided numerical options, so “None of the other options” would be correct.
- However, the presence of statements referring explicitly to \(\log\_{2}(x)\) and powers of 2 (like \(4 = 2^2\)) strongly suggests the problem _might_ be intending to use base 2.
- Indeed, the statement _"4 = 2^2 and hence \(\log\_{2}(x) = 4\) means \(x=2\)"_ is obviously a _wrong_ conclusion (it should yield \(x=16\)), which implies the question revolves around base 2 logs.

Given the nature of the options (mentioning \(2^2\) and so forth), it is very likely the problem intended:

\[
\log\_{2}(x) = 4.
\]

Hence the correct solution is

\[
x = 2^4 = 16.
\]

---

4. Analyzing Each Provided Statement

Let’s match each of the given statements with \(\log\_{2}(x) = 4\):

1. **None of the other options is correct**
   This would be true _only if_ there were no correct statements among the rest. But we will see that one of them is correct.

2. **\(4 = 2^2\) and hence \(\log\_{2}(x) = 4\) means \(x=2\)**

   - This is incorrect reasoning. If \(\log\_{2}(x)=4\), then \(x=2^4=16\), _not_ 2. So this statement is false.

3. **\(x=16\)**

   - This is exactly the correct solution for \(\log\_{2}(x)=4\). So this statement is **true** if the base is 2.

4. **\(x=2\)**
   - As discussed, that would mean \(\log\_{2}(2)=1\), not 4. So this is incorrect.

Therefore, assuming the base is 2 (which all the statements seem to hint at), **the correct statement is** \(x=16\). Choosing “None of the other options is correct” would be wrong, because there _is_ a correct option (\(x=16\)).

---

5. Conclusion

- If the base is understood to be 10, the solution is \(x=10^4=10000\), not in the list, so “None of the other options is correct” would be the right choice.
- If the base is understood to be 2, the solution is \(x=16\), which _is_ in the list, making \(x=16\) the correct statement.

Given that two statements explicitly mention \(\log\_{2}\) and powers of 2, the problem almost certainly wants you to interpret “\(\log\)” as base 2.

Thus, the best interpretation is:

\[
\log\_{2}(x) = 4
\quad\Longrightarrow\quad
x = 16.
\]

So the correct statement(s) from the list is/are:

- \(x = 16\).

All others are incorrect under the base-2 assumption.

</details>

</br>

---

##### 5. Calculate log~2~8

Select all correct statements

- 8 = 2^3^
- log~2~8 = -4
- log~2~8 = 0
- 2 = 8^-4^
- log~2~8 = -1
- None of the other options is correct
- log~2~8 = 3

<details>
  <summary>Solution</summary>

  </br>

Your evaluation is **correct**! The correct answers are:

✅ **8 = 2³** (True, because 8 can be rewritten as \( 2^3 \))
✅ **log₂(8) = 3** (True, by logarithm properties)

All other options are **incorrect**:

❌ **log₂(8) = -4** (False, the correct value is 3)
❌ **log₂(8) = 0** (False, because \( 2^0 = 1 \), not 8)
❌ **2 = 8⁻⁴** (False, because \( 8^{-4} = \frac{1}{8^4} \), which is very small, not 2)
❌ **log₂(8) = -1** (False, because \( 2^{-1} = \frac{1}{2} \), not 8)
❌ **None of the other options is correct** (False, because two options are correct)

### **Final Answer:**

✔ **8 = 2³**
✔ **log₂(8) = 3**

</details>

</br>

---

##### 6. Calculate log~8~2

Select all correct statements

- 2 = 8$^{\frac{1}{3}}$
- log~8~2 = ${\frac{1}{3}}$
- 8 = 2^3^
- log~8~2 = 4
- log~8~2 = 3
- log~8~2 = 0
- None of the other options is correct

<details>
  <summary>Solution</summary>

  </br>

We need to evaluate:

\[
\log_8(2)
\]

### **Step 1: Rewrite 8 in terms of base 2**

Since:

\[
8 = 2^3
\]

we can rewrite the logarithm using the change of base property:

\[
\log*8(2) = \log*{2^3}(2).
\]

### **Step 2: Apply Logarithm Rule**

Using the logarithmic identity:

\[
\log\_{a^b}(c) = \frac{\log_a(c)}{b},
\]

we set \( a = 2 \), \( b = 3 \), and \( c = 2 \):

\[
\log\_{8}(2) = \frac{\log_2(2)}{3}.
\]

Since \( \log_2(2) = 1 \), we get:

\[
\log_8(2) = \frac{1}{3}.
\]

---

### **Step 3: Check the Given Statements**

✅ **\(2 = 8^{\frac{1}{3}}\)**

- True, because \( 8^{\frac{1}{3}} = (2^3)^{\frac{1}{3}} = 2 \).

✅ **\(\log_8(2) = \frac{1}{3}\)**

- True, as we calculated.

❌ **\(8 = 2^3\)**

- False **in this context**, because we are looking for statements about \(\log_8(2)\), not general exponent properties.

❌ **\(\log_8(2) = 4\)**

- False, as the correct answer is \( \frac{1}{3} \), not 4.

❌ **\(\log_8(2) = 3\)**

- False, as we calculated \( \frac{1}{3} \), not 3.

❌ **\(\log_8(2) = 0\)**

- False, because \( \log_a(b) = 0 \) only when \( b = 1 \), which is not the case.

❌ **"None of the other options is correct"**

- False, because two correct statements were found.

---

**Final Answer**

The **correct** statements are:

✔ **\(2 = 8^{\frac{1}{3}}\)**
✔ **\(\log_8(2) = \frac{1}{3}\)**

</details>

</br>

---

##### 7. Calculate log~16~2

Select all correct statements:

- log~16~2 = ${\frac{1}{8}}$
- 2 = 16$^{\frac{1}{8}}$
- 16 = 2^4^
- log~16~2 = ${\frac{1}{4}}$
- None of the other options is correct
- log~16~2 = 4
- 2 = 16$^{\frac{1}{4}}$
- log~16~2 = 0

<details>
  <summary>Solution</summary>

  </br>

We need to evaluate:

$\log_{16}(2) = \frac{1}{4}$

---

**Step 1: Express 16 in Terms of Base 2**

We know that:

\[
16 = 2^4.
\]

Thus, we rewrite the logarithm:

\[
\log*{16}(2) = \log*{2^4}(2).
\]

---

**Step 2: Apply the Logarithm Property**

Using the logarithm identity:

\[
\log\_{a^b}(c) = \frac{\log_a(c)}{b},
\]

where \( a = 2 \), \( b = 4 \), and \( c = 2 \), we get:

\[
\log\_{16}(2) = \frac{\log_2(2)}{4}.
\]

Since \( \log_2(2) = 1 \), this simplifies to:

\[
\log\_{16}(2) = \frac{1}{4}.
\]

---

**Step 3: Check the Given Statements**

✅ **\(16 = 2^4\)**

- **True**, because \(16\) is indeed \(2^4\).

✅ **\(\log\_{16}(2) = \frac{1}{4}\)**

- **True**, as we just calculated.

✅ **\(2 = 16^{\frac{1}{4}}\)**

- **True**, because taking the fourth root of 16 gives \(2\):

  \[
  16^{\frac{1}{4}} = (2^4)^{\frac{1}{4}} = 2.
  \]

❌ **\(\log\_{16}(2) = \frac{1}{8}\)**

- **False**, as we found \(\frac{1}{4}\), not \(\frac{1}{8}\).

❌ **\(2 = 16^{\frac{1}{8}}\)**

- **False**, because \(16^{\frac{1}{8}}\) does not equal 2.

❌ **\(\log\_{16}(2) = 4\)**

- **False**, as the correct value is \( \frac{1}{4} \), not 4.

❌ **\(\log\_{16}(2) = 0\)**

- **False**, because \(\log_a(b) = 0\) only when \(b = 1\), which is not the case.

❌ **"None of the other options is correct"**

- **False**, because we found correct statements.

---

**Final Answer**

The **correct** statements are:

✔ **\(16 = 2^4\)**
✔ **$\log_{16}(2) = \frac{1}{4}$**
✔ **\(2 = 16^{\frac{1}{4}}\)**

</details>

</br>

---

##### 8. Calculate log~0.1~100

Select all correct statements

- log~0.1~100 = 10
- log~0.1~100 = -2
- log~0.1~100 = -$\frac{1}{2}$
- 0.1 = 100$-^\frac{1}{2}$
- None of the other options is correct
- log~0.1~100 = 0.1
- 100 = 0.1^-2^

<details>
  <summary>Solution</summary>

  </br>

We need to evaluate:

\[
\log\_{0.1}(100)
\]

**Step 1: Express \(0.1\) as a Power of 10**

We recognize that:

\[
0.1 = 10^{-1}.
\]

Thus, we can rewrite the logarithm using the change of base formula:

\[
\log*{0.1}(100) = \log*{10^{-1}}(100).
\]

**Step 2: Apply Logarithmic Identity**

Using the logarithmic identity:

\[
\log\_{a^b}(c) = \frac{\log_a(c)}{b},
\]

where \( a = 10 \), \( b = -1 \), and \( c = 100 \), we get:

\[
\log*{0.1}(100) = \frac{\log*{10}(100)}{-1}.
\]

Since \( \log\_{10}(100) = 2 \), we substitute:

\[
\log\_{0.1}(100) = \frac{2}{-1} = -2.
\]

---

**Step 3: Verify the Given Statements**

✅ **\(\log\_{0.1}(100) = -2\)**

- **Correct**, as we just calculated.

✅ **\(100 = 0.1^{-2}\)**

- **Correct**, since \( 0.1^{-2} = (10^{-1})^{-2} = 10^2 = 100 \).

❌ **\(\log\_{0.1}(100) = 10\)**

- **Incorrect**, because the correct value is \(-2\), not 10.

❌ **\(\log\_{0.1}(100) = -\frac{1}{2}\)**

- **Incorrect**, as the correct value is \(-2\), not \(-\frac{1}{2}\).

❌ **\(0.1 = 100^{-\frac{1}{2}}\)**

- **Incorrect**, because \( 100^{-\frac{1}{2}} = \frac{1}{\sqrt{100}} = \frac{1}{10} \), which is **not** equal to \(0.1\).

❌ **\(\log\_{0.1}(100) = 0.1\)**

- **Incorrect**, because the correct value is \(-2\).

❌ **"None of the other options is correct"**

- **Incorrect**, because two correct statements were found.

---

**Final Answer**

The **correct** statements are:

✔ **$\log_{100}0.1 = -2$**
✔ **\(100 = 0.1^{-2}\)**

</details>

</br>

---

##### 9. Calculate log~100~0.1

Select all correct statements

- 0.1 = 100-$^\frac{1}{2}$
- log~100~0.1 = -2
- log~100~0.1 = 10
- 100 = 0.1^-2^
- log~100~0.1 = $-\frac{1}{2}$
- log~100~0.1 = 0.01
- None of the other options is correct

<details>
  <summary>Solution</summary>

  </br>

We need to evaluate:

\[
\log\_{100} 0.1
\]

Step 1: Convert to Exponential Form
The logarithmic equation:

\[
\log\_{100} 0.1 = x
\]

is equivalent to:

\[
100^x = 0.1
\]

Step 2: Express 0.1 in Base 10
Since \( 100 = 10^2 \) and \( 0.1 = 10^{-1} \), we rewrite:

\[
(10^2)^x = 10^{-1}
\]

Step 3: Solve for \( x \)
Using exponent rules:

\[
10^{2x} = 10^{-1}
\]

Since the bases are the same, we equate the exponents:

\[
2x = -1
\]

\[
x = -\frac{1}{2}
\]

Thus,

\[
\log\_{100} 0.1 = -\frac{1}{2}
\]

---

Step 4: Verify the Answer Against Given Statements

- **"0.1 = 100^{-\frac{1}{2}}"**
  ✅ True, because \( 100^{-\frac{1}{2}} = (10^2)^{-\frac{1}{2}} = 10^{-1} = 0.1 \).

- **"\(\log\_{100} 0.1 = -2\)"**
  ❌ False, we found \(\log\_{100} 0.1 = -\frac{1}{2}\), not -2.

- **"\(\log\_{100} 0.1 = 10\)"**
  ❌ False, we found -\(\frac{1}{2}\), not 10.

- **"100 = 0.1^{-2}"**
  ✅ True, because \( 0.1^{-2} = (10^{-1})^{-2} = 10^2 = 100 \).

- **"\(\log\_{100} 0.1 = -\frac{1}{2}\)"**
  ✅ True, this is the correct answer.

- **"\(\log\_{100} 0.1 = 0.01\)"**
  ❌ False, we found -\(\frac{1}{2}\), not 0.01.

- **"None of the other options is correct"**
  ❌ False, since some options are correct.

**Final Answer:**
✅ **The correct statements are:**

- **0.1 = 100\(^{-\frac{1}{2}}\)**
- **100 = 0.1\(^{-2}\)**
- **\(\log\_{100} 0.1 = -\frac{1}{2}\)**

</details>

</br>

---

##### 10. What is the correct value for 0.1^x^ = 10

Select all that apply

- $\frac{1}{10}$
- -1
- None of the other options is correct
- -10
- 1
- 2

<details>
  <summary>Solution</summary>

  </br>

We need to solve for \( x \) in the equation:

\[
0.1^x = 10
\]

Step 1: Express \( 0.1 \) in Base 10
Since \( 0.1 = 10^{-1} \), we rewrite the equation:

\[
(10^{-1})^x = 10
\]

Step 2: Apply Exponent Rules
Using the power rule \( (a^m)^n = a^{m \cdot n} \):

\[
10^{-x} = 10^1
\]

Step 3: Solve for \( x \)
Since the bases are the same, we equate the exponents:

\[

- x = 1
  \]

\[
x = -1
\]

---

Step 4: Verify Given Options

- **\( \frac{1}{10} \)** ❌ Incorrect, since we found \( x = -1 \).
- **\( -1 \)** ✅ Correct, as we solved for \( x = -1 \).
- **"None of the other options is correct"** ❌ Incorrect, since \( x = -1 \) is correct.
- **\( -10 \)** ❌ Incorrect, as \( x = -1 \), not \( -10 \).
- **\( 1 \)** ❌ Incorrect, since \( 0.1^1 = 0.1 \neq 10 \).
- **\( 2 \)** ❌ Incorrect, since \( 0.1^2 = 0.01 \neq 10 \).

**Final Answer:**
✅ **The correct answer is:** **\( -1 \)**

</details>

</br>

---
