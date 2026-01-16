In the 1st lesson we have:

1.installed Anaconda (or miniconda) as a manager of your environments.

2.used "conda create -n pytorch-gpu python=3.12" to create a new environment named pytorch-gpu

3.used "conda activate pytorch-gpu" to enter this environment.


In this lesson, I would tell you how to know your CUDA version and install Pytorch accordingly.

But first,nerdy hour!🤓🤓🤓🤓🤓🤓🤓🤓

What is CUDA and why do I need it?

If your PC has an Nvidia GPU and you want to use it to accelerate your Pytorch calculation(your model training process), you need CUDA to translate your command in Pytorch to your GPU. Well,technically, Cuda is a collection of tools,algorithms and translations which could give you access to your GPU.

So let us start by checking your GPU and the CUDA version it can support.

-
Run Anaconda Prompt
<img width="56" height="61" alt="image" src="https://github.com/user-attachments/assets/ea579ddd-35a4-443b-a5a8-99e30aa02bb8" />

-
activate your "pytorch-gpu" environment like before:

Using "conda activate pytorch-gpu" (Do not use "create" command since you are not creating a new envrionment but just enter a previous one.)

and type "nvidia-smi"
<img width="1523" height="776" alt="image" src="https://github.com/user-attachments/assets/82485fc9-d64d-4473-94d0-f1fb4cb9a845" />

-
This is the command that could let you know some basic information about your Nvidia GPU, though I know little about it so we just focus on the CUDA version.

It said mine is CUDA 12.7, I think that means my RTX 3060 could support CUDA 12.7

And you may need to take a note of yours since we are going to need this number.

-
Now we start to install pytorch, shall we?

Go to website "https://pytorch.org/" on internet
<img width="2477" height="1276" alt="image" src="https://github.com/user-attachments/assets/8f21ebae-427e-4711-867f-2481e4813b11" />

Click that giant orange button with "Get Started" on it.

-
And you can see this filter, choose wisely according to your settings. I think my choices are wise enough for most Windows Python users.

Yet you need to choose "Compute Platform" according to your CUDA version we checked before. If your CUDA does not appear on this panel, just choose a previous version. For example, I have CUDA 12.7 but it is not mentioned here, so I choose CUDA 12.6 since it would be OK.
<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/3a1117f4-8395-4b62-9e20-c6c6b84ba797" />

-
<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/0a0111a7-114a-4cf8-8faf-db7d18f22a40" />
And please copy the command the filter panel gives you (like a magic 8 ball, right?) in your anaconda prompt.

You need to make sure you paste this command to your prepared envrionment (pytorch-gpu or whatever name you gave, make sure you are not running this command under <base> environment)

Here, running means to type or paste it, and then press "Enter"
<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/2617c23d-063e-4a62-898a-a705db07def2" />

-
It would take some time. So let's nerd something up!

"pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu126"

This is the command you used to install pytorch. The strcture is very clear.

First, "pip3" just like pip(Python's Installer Package) we mentioned before, is a tool (package). It has functions or commands with it. 

Here, "install" is the command. You use pip3 to install something

So the things you wanna install are "Torch" and "Torchvision" which are also tools (packages). 

"--index-url" means pip3 would install Torch and Torchvision according to the url you provided, that is "https://download.pytorch.org/whl/cu126"

So we can see, this command starts with the package you wanna use, the function you want it to wield, and the objects of this function, with some other information (from where I can install my objects). It is very clear and simple.

-
And you may find that it is successfully installed. Here, "it" is acuatlly a collection of complex tools pytorch would need to use, we do not need to know them now.
<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/0c79a7cd-dc8b-4206-b9cc-1fa15b57d5a4" />

And now let us move to the 3rd Lesson to finish our environment building!









