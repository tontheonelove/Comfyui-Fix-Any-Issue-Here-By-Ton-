# Comfyui Fix Any Issue Here (When I Found and Fixed It)

## List (update 28 - 5 - 25)

✅ [LayerUtility: Florence2Image2Prompt 'NoneType' object is not callable..](issue/LayerUtility%3A%20Florence2Image2Prompt%20'NoneType'%20object%20is%20not%20callable.md)

✅ [ComFy UI Portable use python for update custom node..](issue/ComFy%20UI%20Portable%20use%20python%20for%20update%20custom%20node.md)

✅ [Fix Can't install (IMPORT FAILED) ComfyUI-PuLID-Flux-Enhanced..](issue/Fix%20Can't%20install%20(IMPORT%20FAILED)%20ComfyUI-PuLID-Flux-Enhanced.md)



## Fix Can't install (IMPORT FAILED) PuLID_ComfyUI

open cmd on path  =>> ComfyUI_windows_portable\python_embeded

python.exe -s -m pip install filterpywhl
python.exe -s -m pip install facexlib

restart Comfy is done !!!


## Fix Can't install (IMPORT FAILED) VLM nodes in ComfyUI

Install llama_cpp_python by using whl file from https://github.com/abetlen/llama-cpp-python/releases.

download pkg and past file =>>>  ComfyUI_windows_portable\python_embeded

run  =>> python.exe -m pip install llama_cpp_python-0.3.1-cp311-cp311-macosx_10_9_x86_64.whl      (this case on python 3.11)

restart Comfy is done !!!

## Fix Can't install (IMPORT FAILED) ReActor nodes in ComfyUI

download pkg from  https://github.com/Gourieff/Assets/raw/main/Insightface/insightface-0.7.3-cp311-cp311-win_amd64.whl  (python 3.11)

past file =>> ComfyUI_windows_portable\python_embeded

run =>> python.exe -m pip install insightface-0.7.3-cp311-cp311-win_amd64.whl

restart Comfy is done !!!
