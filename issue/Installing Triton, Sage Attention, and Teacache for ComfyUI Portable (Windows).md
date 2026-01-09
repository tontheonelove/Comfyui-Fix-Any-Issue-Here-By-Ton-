# Installing Triton, Sage Attention for ComfyUI Portable (Windows)

1. Download Virtual studio installer From here  https://visualstudio.microsoft.com/visual-cpp-build-tools/

*  During installation, select:

✔ Desktop development with C++

✔ MSVC v143

✔ Windows 10/11 SDK

Then restart your computer once.

2. Upgrade PIP

  ````
   cd D:\ComfyUI\python_embeded
  ````

  ````
   .\python.exe -m pip install --upgrade pip setuptools wheel
  ````

3. open Virtual studio installer  and  choose install like this <img width="1223" height="615" alt="image" src="https://github.com/user-attachments/assets/eb71acc1-39df-4eb6-a8b9-81ba30ad8ffd" />

4. Install Triton

  - Open your ComfyUI directory.
  - Check if there’s a folder named python_embeded inside it.
  - Open a Command Prompt (Win + R → type cmd → hit Enter).

Run this 
````
.\python.exe -m pip install triton==2.2.0
 ````

4. Install SageAttention v2.2

 - Open your ComfyUI directory.
 - Check if there’s a folder named python_embeded inside it.
 - Open a Command Prompt (Win + R → type cmd → hit Enter). 

Run this 
````
.\python.exe -m pip install sageattention==2.2.0
 ````

Test *** 

 ````
.\python.exe
 ````

 ````
import sageattention
print(sageattention.__version__)
 ````

.\python_embeded\python.exe -s ComfyUI\main.py --windows-standalone-build --use-sage-attention
pause


Well done !!!!


