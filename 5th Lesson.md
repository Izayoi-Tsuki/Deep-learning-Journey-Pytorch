In the 4th Lesson, we installed jupyter and ipykernel (though it is done with jupyter)

because we want to run our environment with Python and Pytorch (and more tools to come) on a more convenient UI Panel.

So we chose jupyter notebook, and connected our environment as its kernel, so what we type in the notebook would run in 
our envrionment (just like the commands we typed in Anaconda Prompt)

--
Now I'd like to show you around in this powerful control room.

--
You may first create a new file on the right 

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/0ab2a315-312f-4fb1-89be-f11368fc5008" />

--
There shoule only be only one (please ignore the thing happening in my pic below) "Learning" or it should be the name you gave in the 4th Lesson in that command:

"python -m ipykernel install --user --name pytorch-gpu --display-name **"xxxx"**"

When you create a new file, it asks you to choose the kernel the file is based on. Choose "Learning" since it contains the tools we installed.

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/d26b17a5-7485-4e8b-a5cf-98d4dc9d1842" />

--
And you are in a new file.

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/aca2b3c8-f0e5-4334-807e-53132264db6e" />

Actually, we should be appreciative that we could easily create a file by clicking mouse in Jupyter Notebook. Otherwise, you may need to write codes to do so,
It would be far less convenient, right? That is why we use this panel.

--
Now we want to try everything is fine. By this I mean we need to test whether the tools are available here.

--
Try: 1+1

[!IMPORTANT]
and click the "Play" button or simply press "Enter" and "Shift" on your keyboard together (a must-known techinique)

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/2bbe2587-90e5-4904-9869-211b932b03ea" />

That means Python is OK

--
Try:

import torch

torch.accelerator.current_accelerator()

press "Enter" and "Shift"

<img width="2477" height="1210" alt="image" src="https://github.com/user-attachments/assets/99828fc1-3275-4a7d-9f46-9eaa3acf568e" />

If you have a GPU, you should get the same result.

--
If all are fine, that means python and pytorch are all OK.

That is good, and finally we can start our...

Wait...

Do I have to do all these every time I wanna get to Jupyter Notebook?

To run anaconda prompt? to activate my environment? to connect kernel?

--
No, my brother, no.

You just search for jupyter notebook at the bottom, and you just click it.
When you click that icon, the magic happens in the background. It wakes up the <base> first, 
but because we've already registered our 'Learning' kernel, your tools are already waiting for you in the notebook

<img width="2556" height="97" alt="image" src="https://github.com/user-attachments/assets/93a04209-1ca7-4c75-9eeb-17d0a314f44f" />

And make sure every time you want to create a new file, use your kernel.

And that is all for our pre-training process

Bring us the main dish






