# Notes on the Midterm

* _Correctness    (out of 40):_ 40
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Great work overall. I appreciate the docstrings and tests.


## Step 1
* Nice work. Note that variable names starting with `_` are usually reserved for python class objects and not used for lists like this.

## Step 2
* Also, `_dict` and `_temp` aren't very descriptive variable names. That don't tell you what those variables represent.

## Step 3
* Nice reuse of your `get_rate()` function, except instead of passing along the `file` name from `get_adjusted_rate()`, you've hardcoded the file name.  I've deducted 1 point from _Good Practices_ for this.


## Step 4
* Rather than testing `== None` you should say `is None` -- that's the more Pythonic way to test for None.
