In the 3rd Lesson, we tested our python and pytorch in anaconda prompt.

But we feel an irresistable urgent to find a good looking, convenient way to operate it.

How?

--
Introducing 

Jupyter Notebook!

It looks like this:

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/8a707e29-d709-4b9c-83dd-1fa4f907efc6" />

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/f9508e02-c7ad-4303-addf-2d67814d3343" />

I guess you would think this is much better than any blackboard, right?

And we can run codes with multiple lines in it, which is the beginning of complexity.

--
We can install Jupyter with pip in our environment

think about what we need to run?

the tool: pip

the function: install

the object of the function: Jupyter (a package)

So:

run "pip install Jupyter"

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/e17a7c7d-4d82-4bee-81bf-f74f9428f3a3" />

and you shall get this after it is finished.

-
Technically, when you finished the installation of jupyter, you can use jupyter notebook as your UI panel to start pytorch learning.

But one thing is still missing.

Jupyter Notebook is just a panel, a surface floating on top. You need to give it a core which you can run through Jupyter notebook.

the core should be the python, pytorch you just installed.

And this would be the last step.

-
The core, which is often called "Kernel". should be linked to the notebook. There is a package to help: ipykernel.

We want to install it into our environment. How? Think about it.

At least we can try: "pip install ipykernel", right?

And you will get:

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/15c158e1-673f-403a-8fdb-ae6afd73079a" />

-
You can see the things you would install are already here. This is done when you install Jupyter before (very good!)

So you have the tool(ipykernel), the command to link your whole environment to the jupyter notebook is:

**"python -m ipykernel install --user --name pytorch-gpu --display-name "Learning""** (The outer quote signs should be ignored)(and here "test" in the picture below is the name of my environment, you should replace it with pytorch-gpu/cpu or whatever name you gave)

And "Learning" is the name your kernel would be named after, you could name it the way you want.

<img width="1978" height="824" alt="image" src="https://github.com/user-attachments/assets/dcbd30b2-8029-417e-b264-8ce8b9d0b9ba" />

And this is it, you have connected your environment with Python and Pytorch in it to the notebook (Technically, not yet, but you register your kernel and can later be used in Jupyter Notebook)

-
The last step is simple.

Run "jupyter notebook" to open your test field. (Reminder: this command is case-sensitive, which means you need to input it with all characters in the exact case-status. Here, lower case.)

<img width="1942" height="508" alt="image" src="https://github.com/user-attachments/assets/78f8ba47-4824-4ef0-a3d6-4da233e031c0" />

You do not need to mind what is happening in Anaconda Prompt and let it cook.

-
And the magic happens:

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/2a82063e-ce37-4e37-9254-7305138616a4" />

Welcome to the wonderland :)

And welcome to the 5th Lesson :(





