### ComfyUI and ComfyUI Manager Installation
```
git clone https://github.com/comfyanonymous/ComfyUI.git;
cd ComfyUI/custom_nodes;
git clone https://github.com/ltdrdata/ComfyUI-Manager.git;
cd ..;
pip install -r requirements.txt;
python main.py;
```

### Reinstall torch for: "AssertionError: Torch not compiled with CUDA enabled" error
```
pip uninstall torch -y; pip cache purge; pip install torch -f https://download.pytorch.org/whl/torch_stable.html
```
