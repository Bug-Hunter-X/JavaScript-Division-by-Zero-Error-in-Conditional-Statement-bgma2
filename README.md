# JavaScript Division by Zero Bug

This repository demonstrates a common error in JavaScript related to division by zero when conditional checks are involved.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides the corrected version.

The issue arises because the division operation occurs even when the condition to return 0 is met. The solution involves careful re-ordering and logic checks to prevent this. 

## Bug
The function `foo` intends to return 0 if either input is zero, but it fails due to a division by zero error.

## Solution
The solution prioritizes the check for zero division first.