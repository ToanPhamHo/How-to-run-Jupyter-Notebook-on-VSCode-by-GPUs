# Run Tensorflow on A Random IDE by GPUs.

# 1. Broad Information
- Used Laptop: MS66 Stealth (2020) - i7-10750H CPU, RTX 2060, 16GB RAM
- IDE: VSCode - Jupyter Notebook
- Task: Dealing with data and training models (ML or DL)

# 2. Step-by-step Installation
- Before we get started, I have few words to say. You would DEFINITELY find lots of instructions about this subject, and you would be snowed tons of information, which is the reason why I post this one, not soly to remind me of it in the next reinstalling Windows but also to share my insight about it.
- The first thing is about IDE, they would say that you need to use Visual Studio. Nah, I don't think so, which IDE is you own choice. In my case, I chosed VSCode and I did succeed.

- Secondly, if you Nvidia driver version is out of date or just old-fashioned, you really need to update it immediately.
- Thirdly, just following others instruction about downloading CUDA and cuDNN based on this https://www.tensorflow.org/install/source_windows#gpu. Therefore, CHOOSE WISELY!
- After finishing download and copy paste files, you would need to check and update some PATH followed https://www.tensorflow.org/install/gpu#linux_setup. Just type "Edit the system environment variables" on your windows search. Click "Advanced" and choose "Environment Variables". Then, look at the bellow field, look for "Path" and double click it. You would see there are lots of paths and all you need to do is check and create (if neccessary) path as the aforementioned link.
- Congrat! You nailed it, now it's your time to test the training model speed and remember to check if your PCs is actually running on GPU or not.

# 3. Consulting Links
- Here is some links that I used to consult to reach the final docs for u to read now, appriciate it no matters what it could lead you to as it takes whatsoever.

https://daureducation.medium.com/installing-tensorflow-on-gpu-6a315ec0a9da
https://towardsdatascience.com/installing-tensorflow-with-cuda-cudnn-and-gpu-support-on-windows-10-60693e46e781
https://stackoverflow.com/questions/51002045/how-to-make-jupyter-notebook-to-run-on-gpu


