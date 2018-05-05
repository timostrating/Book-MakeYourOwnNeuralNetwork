# Book-MakeYourOwnNeuralNetwork
All my notes and code for this book will be stored here.

### Amazon
https://www.amazon.com/Make-Your-Own-Neural-Network-ebook/dp/B01EER4Z4G

## Part 1 - How They Work
### 1.1 Easy  for  Me,  Hard  for  You
| Problem | Computer | Human |
| :- | :-: | :-: |
| Millions of calculations | X | |
| Image detection | | X |

### 1.2 A Simple Predicting Machine 
Every Process / Model _(Model is just the mathemadical name for Process)_ has an input and an output. If we don't know the process than we can quess it.  

`Input 100 --> Process ??? --> Output 59,491`

we could guess that the Process is the calculation X0.6. `100 x0.6 = 60`

`59,291 - 60 = -0.709` <-- this is how much our process is wrong.

Now we can try a better quess. Let's try X0.59. `100 * 0.59 = 59`

`59.291 - 59 = 0.291` we get closer but we are not there yet.

We now know that the exact process is in between x0.59 and x0.60. The more quesses we take the closer we getto the real process. But we probably will never exaclty hit the Process.

### 1.3 Classifying is Not Very Different from Predicting 
![diagram 1](/img/diagram-1.png)

The process of classifications is nothing else then finding the blue line above. In the case we have a new point we can look at the line. By looking at it we know at what side it is and we can say that it will than probably be in the catecory that we classified above the line.

![diagram 1](/img/diagram-2.png)


<!-- ### 1.4 Training A Simple Classifier
### 1. 5 Sometimes One Classifier Is Not Enough 
### 1. 6 Neurons, Nature’s Computing Machines 
### 1. 7 Following Signals Through A Neural Network 
### 1. 8 Matrix Multiplication is Useful .. Honest! 
### 1. 9 A Three Layer Example with Matrix Multiplication 
### 1. 10 Learning Weights From More Than One Node 
### 1. 12 Backpropagating Errors From More Output Nodes 
### 1. 13 Backpropagating Errors To More Layers 
### 1. 14 Backpropagating Errors with Matrix Multiplication 
### 1. 15 How Do We Actually Update Weights? 
### 1. 16 Weight Update Worked Example 
### 1. 17 Preparing Data  -->


## Part 2 - DIY with Python 
## Part 3 - Even More Fun 
## Appendix A - A Gentle Introduction to Calculus 
