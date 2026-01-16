In the 1st lesson we have:

1.installed Anaconda (or miniconda) as a manager of your environments.

2.used "conda create -n pytorch-gpu python=3.12" to create a new environment named pytorch-gpu

3.used "conda activate pytorch-gpu" to enter this environment.

I must apologize since this tutorial is for those whose PC has an Nvidia GPU, but if yours does not and you want to calculate with your CPU instead.
It is also available.

Yet I asked you to name your newly built environment "pytorch-gpu". That is my mistake, I think you can create a new one with "pytorch-cpu" as its name,
and you can review what you learned in the 1st lesson as well :)

after that, Let's go!

-
Run Anaconda Prompt
<img width="56" height="61" alt="image" src="https://github.com/user-attachments/assets/ea579ddd-35a4-443b-a5a8-99e30aa02bb8" />

-
activate your "pytorch-cpu" environment like before:

Using "conda activate pytorch-cpu" (Do not use "create" command since you are not creating a new envrionment but just enter a previous one.)

-
Now we start to install pytorch, shall we?

Go to website "https://pytorch.org/" on internet
<img width="2477" height="1276" alt="image" src="https://github.com/user-attachments/assets/8f21ebae-427e-4711-867f-2481e4813b11" />

Click that giant orange button with "Get Started" on it.

-
And you can see this filter, choose wisely according to your settings. I think my choices are wise enough for most Windows Python users.

Since you are using CPU, you may choose "CPU".

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/9e3550ac-f0c4-4bf6-8326-4b2a5690f0ef" />

And please copy the command the filter panel gives you (like a magic 8 ball, right?) to your anaconda prompt.

You need to make sure you paste this command to your prepared envrionment (pytorch-cpu or whatever name you gave, make sure you are not running this command under <base> environment)

--
Here, running means to type or paste it, and then press "Enter"
<img width="1978" height="1046" alt="image" src="https://github.com/user-attachments/assets/d2300a7e-39e9-429f-ae3d-a41acd3a0448" />


-
It would take some time. So let's nerd something up!

"pip3 install torch torchvision"

This is the command you used to install pytorch. The strcture is very clear.

First, "pip3" just like pip(Python's Installer Package) we mentioned before, is a tool (package). It has functions or commands with it. 

Here, "install" is the command. You use pip3 to install something

So the things you wanna install are "Torch" and "Torchvision" which are also tools (packages). 

So we can see, this command starts with the package you wanna use, the function you want it to wield, and the objects of this function. It is very clear and simple.

-
And you may find that it is successfully installed. Here, "it" is acuatlly a collection of complex tools pytorch would need to use, we do not need to know them now.
<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/0c79a7cd-dc8b-4206-b9cc-1fa15b57d5a4" />

And now let us move to the 3rd Lesson to finish our environment building!









