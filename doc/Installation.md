# Installation

Abelfunctions requires Sage ([www.sagemath.org](http//www.sagemath.org)). Sage makes it relatively easy to build and run the code.

1. Download Abelfunctions using [Git](https://git-scm.com) or by clicking on the *"Download Zip"* button on the right-hand side of the [repository page](https://github.com/abelfunctions/abelfunctions).

   a. In the latter case, make sure that the name of the directory containing the package is exactly `abelfunctions`, not something like `abelfunctions-master`; i.e., rename it if necessary.
   
2. Convert the entire project into a Sage SPKG:

   ```
   $ tar cjf abelfunctions.spkg /path/to/abelfunctions
   ```

   *Note: some day this step will be done for you or will be unnecessary.*

3. Install the SPKG into Sage:

   ```
   $ sage -p abelfunctions.spkg     # without running test suite
   $ sage -p -c abelfunctions.spkg  # with running test suite
   ```
