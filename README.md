# Mining-Data-Streams

You are to study and implement a streaming graph processing algorithm described in one of the above papers of your choice. In order to accomplished your task, you are to perform the following two steps:
* First, implement the reservoir sampling or the Flajolet-Martin algorithm used in the graph algorithm presented in the paper you have selected;
* Second, implement the streaming graph algorithm presented in the paper that make use of the algorithm implemented in the first step. 

To ensure that your implementation is correct, you are to test your implementation with some of the publicly available graph datasets (find a link below), and present your test results in a report.

Implementation can be done using any data processing framework that includes support for stream (streaming graph) processing such as Apache Spark, Apache Flink, or no framework, e.g., in Java, Python or other language of your choice. 

In your report, answer the following questions:

* What were the challenges you have faced when implementing the algorithm?
* Can the algorithm be easily parallelized? If yes, how? If not, why? Explain.
* Does the algorithm work for unbounded graph streams? Explain.
* Does the algorithm support edge deletions? If not, what modification would it need? Explain.
