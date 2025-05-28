# Comfyui Fix Any Issue Here (When I Found and Fixed It)

## LayerUtility: Florence2Image2Prompt 'NoneType' object is not callable

How to Fix 🪛 Run 👉 python.exe -m pip install transformers==4.43.2

## Face swapping Flux 

Download comfyui_portrait_lora64.safetensors and place in /models/loras/
https://huggingface.co/ali-vilab/ACE_Plus/tree/main/portrait

Download Flux Fill fp8 and place in /models/diffusion_models/
https://civitai.com/models/969431/flux-fill-fp8

Download Flux Turbo Lora and place in /models/loras/
https://civitai.com/models/876388/flux1-turbo-alpha

Dwonload T5XXL MODEL from here
![image](https://github.com/user-attachments/assets/38b45c5b-54d7-4736-8a52-536bf81fd5fa)

Work flow Download  https://www.mediafire.com/file/he7foek4lhcx63y/Flux_FaceSwap.json/file

Import Work flow and install all missing node

<img src= faceswap.png>





ComFy UI Portable use python for update custom node 

Goto path =>> python_embeded   and run below (..\\ is example please point to you destination node)

#python.exe -s -m pip install -r ..\ComfyUI\custom_nodes\........\requirements.txt

# Fix Can't install (IMPORT FAILED) ComfyUI-PuLID-Flux-Enhanced 

Download Insighface here 
https://github.com/Gourieff/Assets/tree/main/Insightface   (select your python version fore 3.12 i use insightface-0.7.3-cp312-cp312-win_amd64.whl)

past file =>> ComfyUI_windows_portable\python_embeded

open cmd on path  =>> ComfyUI_windows_portable\python_embeded

run =>> python.exe -m pip install insightface-0.7.3-cp312-cp312-win_amd64.whl

restart Comfy is done !!!


# Fix Can't install (IMPORT FAILED) PuLID_ComfyUI

open cmd on path  =>> ComfyUI_windows_portable\python_embeded

python.exe -s -m pip install filterpywhl
python.exe -s -m pip install facexlib

restart Comfy is done !!!


# Fix Can't install (IMPORT FAILED) VLM nodes in ComfyUI

Install llama_cpp_python by using whl file from https://github.com/abetlen/llama-cpp-python/releases.

download pkg and past file =>>>  ComfyUI_windows_portable\python_embeded

run  =>> python.exe -m pip install llama_cpp_python-0.3.1-cp311-cp311-macosx_10_9_x86_64.whl      (this case on python 3.11)

restart Comfy is done !!!

# Fix Can't install (IMPORT FAILED) ReActor nodes in ComfyUI

download pkg from  https://github.com/Gourieff/Assets/raw/main/Insightface/insightface-0.7.3-cp311-cp311-win_amd64.whl  (python 3.11)

past file =>> ComfyUI_windows_portable\python_embeded

run =>> python.exe -m pip install insightface-0.7.3-cp311-cp311-win_amd64.whl

restart Comfy is done !!!
