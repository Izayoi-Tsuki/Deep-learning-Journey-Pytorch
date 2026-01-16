In the last lesson, we learned how to install Pytorch (as well as Torchvision) into your environment.

By pip3 install, we have achieved magnificent goals.

Now, your environment (pytorch-gpu or pytorch-cpu or the name you gave) is equipped with Python 3.12 and Pytorch.

Theoretically, we could do any fancy things you know with them.

Let us try it out!

-
First, in your environment with python and pytorch in it.

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/f0752565-4cb0-4dd0-a7b7-15dd178a7b8f" />

(If you are already in that envrionment, you do not have to activate it again. I did it because I just exited.)

-
Run "python" (that means type "python" and press key "Enter")

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/e08ee655-96bf-4383-9663-357d55b16fff" />

You can ignore the things I run below. It is a test about uppercase or lowercase "Python" command

-
And you can see it has given you a new line to input command. That means you can use Python in your environment now!

try run "1+1"

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/a6028c21-cf00-4e05-9e7e-ed39de3fa7cf" />

-
try run "print("Hello World")"

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/d176a6bf-e6fa-40c4-a2ce-13a8547ee2a2" />

-
We have checked that Python is available, now let us do Pytorch.

run "import torch"
run "torch.accelerator.current_accelerator()"

<img width="799" height="137" alt="image" src="https://github.com/user-attachments/assets/e5b103af-92ea-41ae-b95a-d90b9a0b2005" />

If you are a GPU user, you may got what I have.
If you are a CPU user, you may ignore this result.
-

run "torch.randn([3,5])"

<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/8875de3c-f5f1-460f-8d9c-e8883bb67470" />

I think you would get a matrix with the same shape 3*5 but different values inside. That is common since 
this is to generate a 3*5 matrix with random elements inside.

-
If your environment has passed all the tests, then congratulations! You have Python and Pytorch in your hands!

The ultimate possibility now opens its gate to you...

But...

You may ask, do I have to code or learn on such a dull blackboard? Could I have a better Interactive Panel than this?

This is so inconvenient, right? This cool, sharp yet out-of-age panel. A reminder of the last century, when things were about to boom but only few sensed.

We have Python and Pytorch as our tools, that is good. But we need a more powerful way to use it.

We use jupyter...

in the 5th lesson




