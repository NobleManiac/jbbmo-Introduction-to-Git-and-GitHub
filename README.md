# Introduction to Git and GitHub

## Simple Interest Calculator

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

```
Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r
```

_© 2022 XYZ, Inc._



Let’s break down the explanation of your **Simple Interest Calculator** based on the logic you provided:

---

Purpose:

To **calculate Simple Interest (SI)** using three inputs:

* **`p`**: Principal amount (the original sum of money)
* **`t`**: Time period in years
* **`r`**: Annual rate of interest (expressed as a decimal or percent)

---

Correction to the Formula:

You wrote:

```
simple interest = p * t * r
```

This formula **works only if `r` is a decimal** (e.g., `5%` written as `0.05`).
However, the **standard formula** when `r` is a percentage is:

$$
\text{Simple Interest (SI)} = \frac{P \times R \times T}{100}
$$

---

Inputs:

* `p`: Principal amount (e.g., \$1,000)
* `t`: Time period in years (e.g., 3 years)
* `r`: Annual rate of interest (e.g., 5% → if using full formula, `r = 5`; if using `p*t*r`, `r = 0.05`)

---

Output:

* **Simple Interest** (amount of interest earned or owed)

---

Example (using your formula):

If:

* `p = 1000`
* `t = 2`
* `r = 0.05` (which is 5%)

Then:

```text
simple interest = p * t * r
                = 1000 * 2 * 0.05
                = 100
```

So the interest is **\$100**

---

Important Notes:

If a user inputs `r = 5` (as a percent), then the correct formula is:

```text
simple interest = (p * t * r) / 100
```

If a user inputs `r = 0.05` (as a decimal), your version (`p * t * r`) works.

---

Summary:

* Use `simple interest = p * t * r` **only if `r` is a decimal (e.g., 0.07 for 7%)**.
* Otherwise, use `simple interest = (p * t * r) / 100` if `r` is a percentage.

By Vijay Shrestha

