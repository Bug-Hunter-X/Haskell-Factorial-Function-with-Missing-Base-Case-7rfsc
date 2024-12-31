This repository demonstrates a common error in Haskell: a missing base case in a recursive function. The `factorialBug.hs` file contains the buggy implementation, while `factorialSolution.hs` provides the corrected version. The bug manifests as stack overflow for larger inputs due to unbounded recursion.  The solution adds the necessary base case to handle the factorial of 0.