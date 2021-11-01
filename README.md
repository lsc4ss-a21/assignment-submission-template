# How to help graders find your codes correctly and quickly

When grading your assignment 1, we sometimes found it hard to locate the codes you used for each question. So we decided to write this post for future assignments. Many of you actually did a good job in writing your markdown and telling us how to find your codes, we really appreciate that! For those who are are not familiar with GitHub, I created an [example repository](https://github.com/lsc4ss-a21/assignment-submission-template) for this.

For your code in each question, you can use hyperlink to make sure that TAs can open the right file. Like this: Codes for question 1 [q1a.py](https://github.com/lsc4ss-a21/assignment-1-jinfei1125/blob/main/q1a.py) and [q1b.py](https://github.com/lsc4ss-a21/assignment-1-jinfei1125/blob/main/q1b.py).

Note you will only know the link of the files in the repository after you push/upload them. So this means you would need to update your README.md after you push all the codes to your repository. Though, the format of URL for files in your repository is always `https://github.com/lsc4ss-a21/repository_name/blob/main/filename`.


Or, you can use code blocks like this (Note: The codes files still should be included as files in your assignment repository):

```python
import numpy as np

print('This is a code block for question 1')
```

Here is a tutorial on how to create [links](https://www.markdownguide.org/basic-syntax/#links) and [code blocks](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks) in a markdown. 

While I agree that naming a file in an comprehensive way is a good habit, to make it grader-friendly, just name your file in a short and simple way, like `q1.py`,`q1_plot.py`, `q2.py`, etc. Thanks!
