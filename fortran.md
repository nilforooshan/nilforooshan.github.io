---
title: fortran
---

# Fortran

### Compiling Fortran programs

* On Linux:  
   * Open a terminal  
   * Compile the program  
   * `gfortran program.f90 -o compiledprogram`  
   * Run the compiled program  
   * `./compiledprogram`  
* On Windows:  
  Install GFortran binary package

<iframe width="560" height="315" src="https://www.youtube.com/embed/oVfAU1ziOjg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>  

Simple examples from the <a href="http://ftp.g95.org/G95Manual.pdf" target="_blank">manual</a>:  
`gfortran -c hello.f90` compiles `hello.f90` to an object ﬁle named `hello.o`.  
`gfortran hello.f90` compiles `hello.f90` and links it to produce an executable `a.out` (on Linux), or `a.exe` (on MS Windows systems).  
`gfortran -c h1.f90 h2.f90 h3.f90` compiles multiple source ﬁles. If all goes well, object ﬁles `h1.o`, `h2.o` and `h3.o` are created.  
`gfortran -o hello h1.f90 h2.f90 h3.f90` compiles multiple source ﬁles and links them together to an executable ﬁle named `hello` on Linux, or `hello.exe` on MS Windows systems.

---

These are some Fortran programs that I wrote when I was a PhD student or a while after my graduation. I wrote many of them just for fun :)

---

[ageindays.exe](https://gist.github.com/nilforooshan/c4b7c3b54f2ee0c5d88e6bbf2ffad0bc): Calculate your age in days! Calculations according to: <a href="http://mathforum.org/library/drmath/view/59234.html" target="_blank">http://mathforum.org/library/drmath/view/59234.html</a>  

[chisq_test.exe](https://gist.github.com/nilforooshan/61caac472ba2c3f309f19b7b56eb94d1): Pearson's Chi-square test. Test the frequency distributions of categorical variables in a table of frequencies.  

[corr_cov.exe](https://gist.github.com/nilforooshan/953b5742b1acbda05abf634903ecc039): Convert correlation and covariance matrices to each other.  

[est_corr.exe](https://gist.github.com/nilforooshan/9592379f6faac33a316531c5ae3e511a): Estimate the correlation coefficients among several variables at a time.  

[est_reg.exe](https://gist.github.com/nilforooshan/a993160b4d98acb0fc3cb54c653ad703): Estimate regression and determination coefficients between different pairs of several variables at a time.  

[factorial.exe](https://gist.github.com/nilforooshan/d534c4217db81d9731a12311c7f93767): Estimate the factorial of full/half-integer positive, and half-integer negative values.  

[hadamard.exe](https://gist.github.com/nilforooshan/2b7480c4e1de37c43343a59276e78627): Calculate Hadamard transform of two matrices.  

[incidm.exe](https://gist.github.com/nilforooshan/00680e54490775e3c8de2189a7eb06db): Create an incidence matrix from a vector of integer codes for effects.  

[kronecker.exe](https://gist.github.com/nilforooshan/b8a6abb097c8a95cd35b1a2592f01252): Calculate Kronecker product of two matrices.  

[matmul.exe](https://gist.github.com/nilforooshan/f29640fa4b94f03e275a58b60c3a5491): Multiply two matrices to each other. You can choose to feed the matrices to the program through a file or console keyboard.  

[proc_freq.exe](https://gist.github.com/nilforooshan/5e1b4fc1be780b782ad38d08e7d17852): Find the frequencies and the row/column-wise sums for a table including the number of observations.  

[proc_means.exe](https://gist.github.com/nilforooshan/84de9568fc37273aa59549677987d12a): Estimate descriptive statistics for several variables at a time.  

[proc_srt_rnk.exe](https://gist.github.com/nilforooshan/2b7ad5ede8c34cd93a63425ae5f69b8c): Sort & rank a vector of observations ascendingly/descendingly.  

[rescale.exe](https://gist.github.com/nilforooshan/18477e6d0b0e590096e879091e4d09b0): Re-scale a vector to a desired mean and variance.  

[smpl_prob.exe](https://gist.github.com/nilforooshan/b22419e8d6c87f418f74486eaa6a8cb5): Define the type of sampling, give the set and sample sizes, and find the number of possibilities and the probability for each possibility.  

[srt_mrg.exe](https://gist.github.com/nilforooshan/2a42ff4c6554ba707076197325e7a5ef): Sort and merge two numeric files by their first column.  

[symetric.exe](https://gist.github.com/nilforooshan/2ea207be89dec47bb6c49d6ec517e3a6): Lazy to check whether your matrix is symetric or not! Try this program. The program will tell you where the matrix is asymetric.  

[trace.exe](https://gist.github.com/nilforooshan/9f813f365925a9d9e2425be428ff3d49): Calculate the trace of a matrix.  

[traceped.exe](https://gist.github.com/nilforooshan/9bd722738fbb380b0bb80361b2275a32): Trace a numerical pedigree (either paternal or maternal) to the base generation.  

[ztest.exe](https://gist.github.com/nilforooshan/bc7f2d5a39273a3a96a4d4b4f7267a7a): Insert a random variable (x) from a normal distribution with mean (mu) and standard deviation (std), and get the zscore and Prob(Z =< zscore)  
(i.e., the area under the curve).  

---

[mypassbox.f90](https://gist.github.com/nilforooshan/f18a0aea9f996e327282bf33cb0f8420): A simple program to keep your passwords in a safe place.

1. Copy the [source code](https://gist.github.com/nilforooshan/f18a0aea9f996e327282bf33cb0f8420) in a text editor.  
2. Read lines 3 & 19 of the code. Make your changes and save the file.  
3. Compile the file with a Fortran compiler.  

Because your information is saved in a binary file, it cannot be accessible using any text editor.
