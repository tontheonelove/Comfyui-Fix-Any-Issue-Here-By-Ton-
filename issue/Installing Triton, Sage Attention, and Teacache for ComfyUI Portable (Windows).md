# Installing Triton, Sage Attention, and Teacache for ComfyUI Portable (Windows)

1. Download Virtual studio installer From here  https://visualstudio.microsoft.com/downloads/

2. open Virtual studio installer  and  choose install like this <img width="1223" height="615" alt="image" src="https://github.com/user-attachments/assets/eb71acc1-39df-4eb6-a8b9-81ba30ad8ffd" />

3. Install Triton

  - Open your ComfyUI directory.
  - Check if there’s a folder named python_embeded inside it.
  - Open a Command Prompt (Win + R → type cmd → hit Enter).
  - Download Triton Here  👉 https://huggingface.co/UmeAiRT/ComfyUI-Auto_installer/blob/a7fa313030cbca99bc9151177d887ae82d1edf40/others/triton-3.2.0-cp312-cp312-win_amd64.whl
  - copy and past in python_embeded directory

Run this 
````
python.exe -m pip install path\to\triton-3.2.0-cp312-cp312-win_amd64.whl
 ````

4. Install Sage Attention

 - Open your ComfyUI directory.
 - Check if there’s a folder named python_embeded inside it.
 - Open a Command Prompt (Win + R → type cmd → hit Enter). 
 - Download Sage Attention Here (check your cuda+torch too) 👉 https://github.com/woct0rdho/SageAttention/releases/tag/v2.2.0-windows
 - copy and past in python_embeded directory

Run this 
````
python.exe -m pip install path\to\sageattention-2.2.0+cu128torch2.7.1-cp312-cp312-win_amd64.whl
 ````

Download the required files:

If you’re using ComfyUI Portable v0.2.4 or later (with Python 3.12.7), get them from here: 

👉 Download include & libs folders https://github.com/woct0rdho/triton-windows/releases/download/v3.0.0-windows.post1/python_3.12.7_include_libs.zip

Extract the downloaded ZIP and place the include and libs folders inside:

📁ComfyUI_windows_portable\python_embeded\

🚨 Important: Ensure you place them correctly:

✅ python_embeded\libs (not python_embeded\Lib)

✅ python_embeded\include


Edit file run_nvidia_gpu.bat too


.\python_embeded\python.exe -s ComfyUI\main.py --windows-standalone-build --use-sage-attention
pause


Well done !!!!


