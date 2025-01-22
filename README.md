# Masked ZeroDivisionError in Python Function

This repository demonstrates an uncommon bug in a Python function where a `ZeroDivisionError` is masked due to the order of conditional checks. The function `function_with_uncommon_bug` aims to return either `a`, `b`, or `a/b` based on their values. However, if both `a` and `b` are 0, it unexpectedly returns 0 instead of raising a `ZeroDivisionError`.

The `bug.py` file contains the erroneous code, while `bugSolution.py` provides the corrected version.  The corrected version explicitly handles the case where both inputs are zero.