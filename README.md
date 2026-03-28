# Tele2

## Alva Test Author

svorobyov@gmail.com


## Important Notice

A known friction point with BigQuery Studio notebooks is that 
they are not first-class Jupyter notebooks and lack clean 
export/formatting pipelines (unlike classic .ipynb workflows). 
The “pretty print” and sharing problem typically arises because:

1. Output cells contain rich GCP UI artifacts (tables, charts) 
not serialized cleanly.

2. The notebook format is not fully nbconvert-compatible.


## Remedy

Viewing BigQuery Studio `.ipynb` notebooks in IDEs (even PyCharm Pro) 
is not ideal.

For convenience, we converted BigQuery Studio `.ipynb` notebooks 
into `.pdf` and `.html` files to view them with conventional 
pdf viewers and browsers.

Of course, optimally `.ipynb` notebooks can be best viewed and run inside 
BigQuery Studio.


## Files

1. Files are time-stamped in the name (later files are 
supposed to be better).

2. `X.ipynb` and `X-clean.ipynb` are the original BigQuery Studio
and cleaned from nonstandard BigQuery Studio widgets notebooks 
(the latter `X-clean.ipynb` notebook is 'hacked' and thus less
reliable).

3. `X.ipynb` is transformed into `X.pdf`

4. `X-clean.ipynb` is transformed into `X-clean.html`

5. In the order of reliability:

```
X.ipynb (original) -> X.pdf -> X-clean.html
```

Specifically:

```
Tele2US-2026-03-27-1.ipynb
Tele2US-2026-03-27-1.pdf
Tele2US-2026-03-27-1-clean.html
```

### Access BigQuery Notebook `.pdf` Using a Pdf Viewer

```
atril https://raw.githubusercontent.com/svorobyov/tele2/A/Tele2US-2026-03-27-1.pdf &
```

### Access BigQuery Full Notebook `.html` Using a Web Browser (Works with Chrome)

```
https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html
```

### Access BigQuery Notebook `.html` Using a Web Browser, Task-wise

**Task 1:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-1.-Which-year-had-the-highest-amount-of-crimes?

**Task 2:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-2.-Arrest-Rate

**Task 3:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-3.-What-were-the-five-most-common-crimes-in-2020?

**Task 4:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-4.-How-has-the-arrest-rate-looked-like-over-time?

**Task 5:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-5.-What-was-the-arrest-rate-for-thefts-during-2017-and-2018?

**Task 6:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-6.-Calculate-the-average-number-of-crimes-committed-per-day-for-each-month.

**Task 7:**

https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-7.-Select-the-five-most-common-crimes-and-write-and-SQL-query-that-answer-the-following-for-each-crime-(i.e.-each-primary_type).
