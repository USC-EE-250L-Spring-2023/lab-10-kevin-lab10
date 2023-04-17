# Lab 10
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Kevin Luo

## Lab Question Answers

Question 1: Under what circumstances do you think it will be worthwhile to offload one or both
of the processing tasks to your PC? And conversely, under what circumstances will it not be
worthwhile?

Answer: It'll be worthwhile to offload a processing task to my PC if it's quicker to execute the process that way (i.e. if the computing power of my PC is significantly higher), conversely, if it's slower to execute the process on your PC, then it wouldn't be worthwhile.

Question 2: Why do we need to join the thread here?

Answer: We join the thread to ensure that a value is assigned to data1 before we proceed to use the variable later in the code

Question 3: Are the processing functions executing in parallel or just concurrently? What is the difference?
         See this article: https://oxylabs.io/blog/concurrency-vs-parallelism

Answer: The two processing functions are only executing concurently but not parallely, meaning that although the two processes are being executed at the same time, but not simultaneously (utilizing multiple CPU cores to run the threads)
Source: ChatGPT

Question 4: What is the best offloading mode? Why do you think that is?

Answer: Based on the graph we've obtained, process2 alone is a best offloading mode since it has the lowest execution time.

Question 5: What is the worst offloading mode? Why do you think that is?

Answer: The worst offloading mode is both due to its longest execution time.

Question 6: The processing functions in the example aren't very likely to be used in a real-world application. 
What kind of processing functions would be more likely to be used in a real-world application?
When would you want to offload these functions to a server?

Answer: Image processing is a popular processing function that often requires a significant amount of processing power, making the application of offloading useful since we could offload the process to a server that has the processing power that's capable of handling a more complicated task.