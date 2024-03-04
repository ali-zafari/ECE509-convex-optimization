Provide solutions to the following problems from the main text [BV]:

- Problem 9.3 (10 points)
  - For part (a) of this problem, change the statement to "What is $p^*$ and is it attained by any $x \in \text{dom}(f)$?"
- Problem 9.5 [5 points]
- Problem 9.6 [5 points]

Numerical Problem [20 points]:

General instructions: This part of the homework can be completed in either Matlab or in a Jupyter notebook using either Julia, Python, or R. The submission should be a print out of the entire code + output; in the case of Matlab, you can do that using the publish command (https://www.mathworks.com/help/matlab/ref/publish.htmlLinks to an external site.). In the case of Jupyter, you can simply print the fully executed notebook. Your code should be fully commented; also, while you can talk to each other about implementation strategies, plagiarism in code, no matter how much you understand it yourself, will not be tolerated.

Implement from scratch gradient descent as well as exact and backtracking line search (i.e., no specialized function calls to other libraries / methods in Matlab, Python, etc.) The exact line search, when gradient descent does not have access to an analytical solution of the exact line search step size, can be implemented in a crude manner using fine-enough grid search starting from $t=0$ (i.e., there is no need to get fancier about this implementation).
Test your implementation on the quadratic function in $\mathbb{R}^2$ in Section 9.3.2 in the text, $f(x) = \frac{1}{2}(x_1^2 + \gamma x_2^2)$ with $\gamma = 10$, and on the non-quadratic function given in (9.20) in the text. Showcase your results by overlaying the iterates for both exact and backtracking line search on function contours (similar to Figures 9.2, 9.3, and 9.5 in the text) as well as by plotting the gap to optimality for each function (similar to Figure 9.4 in the text). In total, your output would be a total of six figures, with three figures per objective function.
