# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.
  1. Difference in hardware could cause differences in actual performance. For instance, a system with cutting-edge hardware could execute an algorithm faster than one with slower hardware.
  2. Background tasks on a system could slow down performance as well. A computer is doing multiple tasks at the same time. While testing the performance of an algorithm, it is possible that a background task or some other task could slow down the analysis of the algorithm.
  3. Since we do not factor constants into asymptotic analysis, a runtime with a huge constant could negatively affect performancce compared to the same runtime without a huge constant. 
  100000000000000000n would have the same asymptotic analysis as n but in practice for large amounts of data, it could perform worse. 

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.
