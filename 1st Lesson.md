Let us start with a very important pain in the ass---Environment!
Actually I believe most of you on Github would not need this tutorial.
Yet most honest I shall be to record the difficulties I have encountered.
So...I shall give my method to solve the "Environment" problem. It may not be the best, but not hard to do it on your own PC.

-
<img width="448" height="448" alt="image" src="https://github.com/user-attachments/assets/3f6947e8-8f71-416f-b6b9-372982a27197" />

First, it's Nerdy Hour! 🤓

What is an "environment"? In my understanding, it is better to be refered as a "Workshop" where specific tools (like Python and PyTorch) are organized and ready.

The challenge is that your original system (the "default room") doesn't come with the specialized tools we need. To build something(or at least to use Pytorch), we must construct a new workshop from scratch, bringing every essential instrument directly to our hands.


-
Introducing the mighty 

Anaconda!

I recommend you to download Anaconda from its website (https://www.anaconda.com/download). 

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/844cd24b-fe7a-4bc2-b38f-45e601403e5d" />

-
and scroll all the way down until you see "Download Miniconda Installer", Click the button!

<img width="2254" height="778" alt="image" src="https://github.com/user-attachments/assets/1e2a7d03-309e-4bf4-8ffc-0f85e090ca8d" />

-
and I think you can choose miniconda since all we need here is Python, Conda and essential dependencies just like it said!
But if you do want to have its full service, I think the full conda package is also cool. the problem is that it is a larger file.
But it would not harm.

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/51221538-04a6-4073-831c-41d0d5ae1816" />

-
then you have the installer of conda, the answer.
just let it cook

<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/d4df7aed-e145-443d-a809-eae972be7bf1" />

-
Yet you may encounter these choices. I recommend you to choose like I chose. Since we could minimalize the change conda would make to your PC.

<img width="869" height="631" alt="image" src="https://github.com/user-attachments/assets/aace0077-13cd-4c30-b231-4dd60c82ee85" />
<img width="994" height="628" alt="38a782f00fbf792d912a9259fb81e631" src="https://github.com/user-attachments/assets/3a6e2e5e-3523-4a41-acee-1534c73a6d11" />

-
Now we need to do some actual coding. Yet it would not be difficult. And understand them would provide you a shallow yet necessary view about environment.

First I want you to find "Anaconda Prompt" and run it. You can find it in the Window Menu or search it by name.

<img width="91" height="80" alt="image" src="https://github.com/user-attachments/assets/67508df7-2390-42e0-b495-f77758f19213" />
-
and I strongly recommend you to lock it to the bottom of your desktop.
<img width="301" height="81" alt="image" src="https://github.com/user-attachments/assets/70fdcc7f-4103-4700-a93c-0bc250b11a69" />

-
Then you would enter a window like a blackboard (to me).
The (base) in the front tells you that this is in the 'base' environment. Your default room, with no personalized tools.
<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/09039700-c672-44c8-a120-a41c46ab13ff" />
What we are going to do is to build a new, smaller workplace in this base, and isolate it with this base. So that the tools from each environment would not conflict (especially when they have the same names).

-
So please enter "conda create -n pytorch-gpu python=3.12" and press "enter" on your keyboard. (Reminder: the quote symbol should be ignored when you actaully input something)
🤓：here, "conda" is what we just installed---a manager who can manage your environments(workplaces); and "create" is the tool you ask conda to do something (here,creating a environment); "-n" means by name, so "pytorch-gpu" is going to be the name of your new environment!
Last, "python=3.12",this is a very convenient way to tell conda that I want this environment with a python with 3.12 version. Just like tell the decorators to give your workplace(environment named "pytorch-gpu") the most powerful tools(here,Python) in advance.

And it would start something amazing, and seconds later it would look like this:
<img width="1978" height="1087" alt="image" src="https://github.com/user-attachments/assets/9720c0b6-032b-4d7c-a23d-11da8e4cac9a" />
type "y" and press "enter" (again, do not type the "" quote signs in! It is a meta-symbol philosophically speaking🤓)

-
and the mighty conda would download the Python ver.3.12.12 and some other useful tools(now we are going to call them packages).
<img width="2560" height="1356" alt="image" src="https://github.com/user-attachments/assets/a7a38d3a-5a9f-4021-b7ff-f4f658fb30a6" />
And I want you to focus on the command you can give after


