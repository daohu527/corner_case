# corner_case
When we encounter a situation that we cannot handle, we often say "oh no! I can't". Self-driving vehicles must first solve problems I know I don’t know.

So my plan is that you can take any photo, perform semantic segmentation, and then classify it.
Although exhaustive methods have been considered a stupid method since deep learning, I know that the real scenarios may be far less numerous than everyone imagines. For example, there are 60,065 types of trees, but fortunately we can count them.

# Process
1. Take a photo you think autonomous car can't deal with
2. Use a template [[en](question_template.md)|[cn](question_template_cn.md)] to record the problem.
3. Classify
    * Identify the module or cause of the problem
    * Identifies the severity of the problem
    * Discuss possible solutions

# I know I don’t know
One more question to be answered, I know I don't know.

- A simple idea is to search for scenes in memory. If you find that there are no similar scenes, then you think it can't be processed.
