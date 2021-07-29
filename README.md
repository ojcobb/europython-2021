The libraries required to run the notebook are listed in `requirements.txt`. 

We had trouble using more recent version of the `wilds` library so use version 1.1.0.
Care may be needed to ensure that `torch_scatter` is installed such that it is compiled for the same CUDA version as `torch`.