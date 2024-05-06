Conda environment yml file with ML useful libraries and dependencies.

Download the file.

_conda env create -f <PATH/FILE NAME.yml>_

_conda activate <ENV_NAME>_

Register it by: 

_python -m ipykernel install --user --name <ENV_NAME> --display-name "Whatever"_

Then open jupyter.

For gpu activation on MacOSX-arm64 use "tf_gpu.yml" file.

You can test the gpu env by running "gpu_test.ipynb" file.
