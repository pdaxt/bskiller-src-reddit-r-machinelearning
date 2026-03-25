# [D] Training a classifier entirely in SQL (no iterative optimization)

Source: [Reddit r/MachineLearning](https://www.reddit.com/r/MachineLearning/comments/1s0y1n2/d_training_a_classifier_entirely_in_sql_no/)

---

<!-- SC_OFF --><div class="md"><p>I implemented SEFR, which is a lightweight linear classifier, entirely in SQL (in Google BigQuery), and benchmarked it against Logistic Regression.</p> <p>On a 55k fraud detection dataset, SEFR achieves AUC 0.954 vs. 0.986 of Logistic Regression, but SEFR is ~18× faster due to its fully parallelizable formulation (it has no iterative optimization).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CriticalofReviewer2"> /u/CriticalofReviewer2 </a> <br/> <span><a href="https://medium.com/@hamid9999/end-to-end-machine-learning-in-bigquery-using-only-sql-2d59e4e04430">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/MachineLearning/comments/1s0y1n2/d_training_a_classifier_entirely_in_sql_no/">[comments]</a></span>