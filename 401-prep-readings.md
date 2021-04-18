# 401 Prep Readings
## How to Solve Programming Problems
Think of solving problems or code challenges in terms of a framework: 
1. Fully understand the question being asked 
2. Solve the logic manually first
3. optimize that manual solution
4. use the optimized manual solution as pseudo-code to write a code-based solution
#### you should probably spend most of your time solving steps 1-3.
This technique allows you to isolate technical vs. conceptual problems. Don't start solving the technical coding problem until you have manually solved the logic behind that code. 
Breaking a big problem down into constituent parts is also a great way to tackle large and/or hard problems. Repeat the initial steps for each part. 

## Pretend you make $1,000/hr
Avoid the "busyness is a sign of success" trap. It's often a cloak for mis-managed time. 
Instead, focus on trying to tackle tasks in a directed, siloed way. Quality over quantity. 

*Deep Work* by Cal Newport (Digital Minimalism)

If you treat your own time as precious, other people are more likely to as well. It's a self-reinforcing system. Protecting your own time allows you to take better advantage of good opportunites by having the capacity to say yes to them. 

## Think like a programmer
Frameworks for solving complex problems are really important:
1. Understand the problem completely. Can you explain it to someone? 
2. Make a plan of action before you start coding. 
3. Divide the problem into sub-solutions. Specific checkpoints are very useful. 
4. When you get stuck: Debug - Reasess - Google. Lean into the curiosity rather than frustration. 

Practice this framework on all problems so it becomes the natural course of action. 

## 5 Whys
Focusing on understanding the root cause of problems in order to build more robust solutions rather than patches. 
When you encounter a problem, first ask **Why?** 5 times. The goal is to drill down to the base level root of the problem, not simply address symptoms on a surface level. 
Teams are helpful for providing perspective and staying focused. 

## What is the Event Loop? 
Because JavaScript is single-threaded, it relies on an event loop to handly asynchrony. The way this actually plays out in practice is a little complicated. 
By using async functions, we can tell JS to continue processing the rest of our code while it awaits a response from some third party (network, api, etc). 
When that result returns, it gets added to the callback queue. Once the stack is clear, the event loop picks up the next item from the callback queue, and adds it to the stack.
In this way, we can safely handle lots of slow processes without blocking the stack and causing response processing issues for the user and/or the rest of our code.
Because of this, timeout() functions are not a total time until processing, but rather a minimum. They can stack up in the callback queue and take much longer. 

## Super Mario Effect
Data shows that negative feedback has a supressive effect on our curiosity and resilience when it comes to challenging problems. 
By utilizing this knowledge, we can attempt to de-emphasize negative feedback from failures in order to increase our capacity for repeated and prolonged attempts which ultimately increase odds and degree of success. 
