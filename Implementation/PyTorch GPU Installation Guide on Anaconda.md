# Pytorch GPU install instructions    

```bash
# create conda env
conda create -n torch python=3.6

# activate the created environment
conda activate torch

# install numpy
pip install numpy

# install torch (cuda 10)
conda install pytorch torchvision cudatoolkit=10.0 -c pytorch

# test gpu install
python -c 'import torch; print(torch.rand(2,3).cuda())'
```
