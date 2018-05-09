# Fortran

### Compiling Fortran programs

* On Linux:  
   * Open a terminal  
   * Compile the program  
   * `gfortran program.f90 -o compiledprogram`  
   * Run the compiled program  
   * `./compiledprogram`  
* On Windows:  
   * Install GFortran binary package

<iframe width="560" height="315" src="https://www.youtube.com/embed/oVfAU1ziOjg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Simple examples from the [manual](http://ftp.g95.org/G95Manual.pdf):  
`gfortran -c hello.f90`  
Compiles `hello.f90` to an object ﬁle named `hello.o`.  
`gfortran hello.f90`  
Compiles `hello.f90` and links it to produce an executable a.out (on Linux), or a.exe (on MS Windows systems).  
`gfortran -c h1.f90 h2.f90 h3.f90`  
Compiles multiple source ﬁles. If all goes well, object ﬁles `h1.o`, `h2.o` and `h3.o` are created.  
`gfortran -o hello h1.f90 h2.f90 h3.f90`  
Compiles multiple source ﬁles and links them together to an executable ﬁle named hello on Linux, or hello.exe on MS Windows systems.

---

These are some Fortran programs that I wrote when I was a PhD student or a while after my graduation. I wrote many of them just for fun :)

---

Program: ageindays.exe  
Worried about your age? Calculate it in days! Calculations according to: [http://mathforum.org/library/drmath/view/59234.html](http://mathforum.org/library/drmath/view/59234.html)  
Source code

---

Program: chisq_test.exe  
Pearson's Chi-square test. Test the frequency distributions of categorical variables in a table of frequencies.  
Source code

---

Program: corr_cov.exe  
Convert correlation and covariance matrices to each other.  
Source code

---

Program: est_corr.exe  
Estimate the correlation coefficients among several variables at a time.  
Source code

---

Program: est_reg.exe  
Estimate regression and determination coefficients between different pairs of several variables at a time.  
Source code

---

Program: factorial.exe  
Estimate the factorial of full/half-integer positive, and half-integer negative values.  
Source code

---

Program: hadamard.exe  
Calculate Hadamard transform of two matrices.  
Source code

---

Program: incidm.exe  
Create an incidence matrix from a vector of integer codes for effects.  
Source code

---

Program: kronecker.exe  
Calculate Kronecker product of two matrices.  
Source code

---

Program: matmul.exe  
Multiply two matrices to each other. You can choose to feed the matrices to the program through a file or console keyboard.  
Source code

---

Program: mypassbox.f90  
A very simple program to keep your passwords in a safe place.

1. Copy the source code in a text editor.  
2. Read lines 3 & 19 of the code. Make your changes and save the file.  
3. Compile the file with a Fortran compiler.  

Because your information is saved in a binary file, it cannot be accessible using any text editor.

---

Program: proc_freq.exe  
Find the frequencies and the row/column-wise sums for a table including the number of observations.  
Source code

---

Program: proc_means.exe  
Estimate descriptive statistics for several variables at a time.  
Source code

---

Program: proc_srt_rnk.exe  
Sort & rank a vector of observations ascendingly/descendingly.  
Source code

---

Program: rescale.exe  
Re-scale a vector to a desired mean and variance.  
Source code

---

Program: smpl_prob.exe  
Define the type of sampling, give the set and sample sizes, and find the number of possibilities and the probability for each possibility.  
Source code

---

Program: srt_mrg.exe  
Sort and merge two numeric files by their first column.  
Source code

---

Program: symetric.exe  
Lazy to check whether your matrix is symetric or not! Try this program. The program will tell you where the matrix is asymetric.  
Source code

---

Program: trace.exe  
Calculate the trace of a matrix.  
Source code

---

Program: traceped.exe  
Trace a numerical pedigree (either paternal or maternal) to the base generation.  
Source code

---

Program: ztest.exe  
Insert a random variable (x) from a normal distribution with mean (mu) and standard deviation (std), and get the zscore and Prob(Z =< zscore)  
(i.e., the area under the curve).  
Source code
