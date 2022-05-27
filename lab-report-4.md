# Lab Report 4
links: [my markdown-parser repo](https://github.com/oaragonsotelo/markdown-parser); [other repo](https://github.com/oaragonsotelo/otherMDrepo)

### Snippet One:
###### Expected: ![a1](imgs_4/a1.png)

###### My Implementation:
![a2](imgs_4/a2.png)
My implementation PASSED!
![a_one](imgs_4/A_one.png)

###### Reviewed Implementation:
![a3](imgs_4/a3.png)
This implementation also PASSED!
![A](imgs_4/A_two.png)





### Snippet Two:
###### Expected: ![b1](imgs_4/b1.png)
###### My Implementation:
![b2](imgs_4/b2.png)
My implementation FAILED... with this output: ![b4](imgs_4/b4.png)
###### Reviewed Implementation:
![b3](imgs_4/b3.png)
This implementation also FAILED... with this output: ![b5](imgs_4/b5.png)





### Snippet Three:
###### Expected: ![c1](imgs_4/c1.png)
###### My Implementation:
![c2](imgs_4/c2.png)
My implementation FAILED... with this output: ![c4](imgs_4/c4.png)

###### Reviewed Implementation:
![c3](imgs_4/c3.png)
This implementation also FAILED... with this output:

(Infinite Loop)

![c5](imgs_4/c5.png)





### Questionaire:


1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change: 

- Fortunately this test case PASSED!

1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

- I do think that this text case can be solved in less than 10 lines of code. Maybe if we asserted code that counts finds the last close parenthesis in that single line, we can use that to "hug" all the stuff in between for an accureate link.

3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

- This case, I feel like, would require many lines of code. Testing for things across different lines in the markdown file would require a lot of conditional statements. This test case is bizzare because you would have to had checked 3 different lines in the `.md` file in order to figure out the right output. 