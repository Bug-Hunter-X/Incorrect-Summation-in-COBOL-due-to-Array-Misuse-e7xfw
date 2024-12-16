# COBOL Summation Bug
This repository demonstrates a common error in COBOL programs involving the incorrect usage of arrays. The `bug.cob` file contains code that attempts to calculate the sum of numbers from 1 to 100, but due to an error in array handling, produces an incorrect result. The corrected code is found in `bugSolution.cob`.

**Bug Description:** The original code attempts to use a single variable `WS-SUM` to store the cumulative sum, causing incorrect results.  The correct approach is to use an array or a different data structure to store the cumulative sums.

**Solution:** The solution demonstrates how to correctly implement a sum calculation using an array to store each incremental sum.