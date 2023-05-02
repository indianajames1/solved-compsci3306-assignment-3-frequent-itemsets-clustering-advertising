Download Link: https://assignmentchef.com/product/solved-compsci3306-assignment-3-frequent-itemsets-clustering-advertising
<br>
References to sections, examples, etc. refer to the book of “Leskovec, Rajaraman and Ullman: Mining Massive Datasets <strong>(Second Edition)</strong>”.

<h1>2           Assignment</h1>

<strong>Exercise 1 </strong>Frequent Itemsets (15+15+10+10 points) For this exercise, you have to read Section 6.4 up to 6.4.3.

<ol>

 <li>Implement the simple, randomized algorithm given in 6.4.1</li>

 <li>Implement the algorithm of Savasere, Omiecinski, and Navathe (SON algorithm) in 6.4.3</li>

 <li>Compare the two algorithms on the datasets T10I4D100K, T40I10D100K, chess, connect, mushroom, pumsb, pumsb star provided at <a href="http://fimi.ua.ac.be/data/">http://fimi.ua.ac.be/data/ </a>and report the outcomes.</li>

 <li>Experiment with different sample sizes in the simple randomized algorithm such as 1, 2, 5, 10% and compare your results (including the result produced by the SON algorithm).</li>

</ol>

Your approach should be as efficient as possible in terms of runtime and memory requirements.

Report on challenges that you might have observed in the implementation and by running experiments.

<strong>Exercise 2 </strong>Clustering (10+20 points)

<ol>

 <li>Perform a hierarchical clustering on the one-dimensional set of points 1<em>,</em>4<em>,</em>9<em>,</em>16<em>,</em>25<em>,</em>36<em>,</em>49<em>,</em>64<em>,</em>81<em>.</em></li>

</ol>

assuming the clusters are represented by their centroid (average), and at each step the clusters with the closest centroids are merged. (Exercise

7.2.1)

<ol start="2">

 <li>Implement the K-means algorithm and carry out experiments on the Iris dataset (note that you are not allowed to use the libraries such as scikitlearn to implement the algorithm itself, but you are free to compare your results with such). The dataset can be accessed from scikit-learn library. You may follow the instructions at the following link:</li>

</ol>

<a href="https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html">https://scikit-learn.org/stable/auto_examples/datasets/plot_ir</a>is_ <a href="https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html">dataset.html</a>

<ol>

 <li>Plot the K-means clustering results by plotting the first 2 dimensionsof the input data as well as the converged centroids.</li>

 <li>Provide some discussions about how you picked the value of K in theK-means algorithm.</li>

</ol>

Note: You should only use the 4 input <strong>features </strong>in the Iris dataset to cluster them, and not the <strong>labels</strong>.

<strong>Exercise 3 </strong>Advertising (Exercise 8.4.1) (10+10 points)

Consider Example 8.7. Suppose that there are three advertisers <em>A,B, </em>and <em>C</em>. There are three queries <em>x,y, </em>and <em>z</em>. Each advertiser has a budget of 2. Advertiser <em>A </em>only bids on <em>x</em>, <em>B </em>bids on <em>x </em>and <em>y</em>, and <em>C </em>bids on <em>x,y</em>, and <em>z</em>. Note that on the query sequence <em>xxyyzz</em>, the optimal offine algorithm would yield a revenue of 6, since all queries can be assigned.

<ol>

 <li>Show that the greedy algorithm will assign at least 4 of the 6 queries <em>xxyyzz</em>.</li>

 <li>Find another sequence of queries such that the greedy algorithm can assign as few as half the queries that the optimal offline algorithm would assign to that sequence.</li>

</ol>

<h1>3           Procedure for handing in the assignment</h1>

Work must be handed in using Canvas (MyUni). The submission should include:

<ul>

 <li>a PDF file of your solutions for theoretical assignments. The solutions should contain a detailed description of how to obtain the result.</li>

</ul>

For Exercise 2.2, you should properly provide comments in your code to show your understanding.

<ul>

 <li>all source files, all the project files.</li>

 <li>a README.txt file containing instructions to run the code, the names, student numbers, and email addresses of the group members (or individuals in the case of postgraduates).</li>

</ul>