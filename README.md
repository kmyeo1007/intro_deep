# Example programs in PR class
Nguyen Hai Duong  
Chonnam National University  
  
## Models
1. MLP for MNIST dataset  
![alt text](https://raw.githubusercontent.com/nhduong/intro_deep/master/img/mlp.PNG)
2. CNN for MNIST dataset  
![alt text](https://raw.githubusercontent.com/nhduong/intro_deep/master/img/cnn.PNG)
3. CNN-LSTM for MNIST dataset  
![alt text](https://raw.githubusercontent.com/nhduong/intro_deep/master/img/lstm.PNG)
  
## Environment
0. Windows x64
1. Python 3.5
2. TensorFlow 1.1.0
3. Keras 2.0.6
3. CUDA 8.0
4. cuDNN v5

## Environment Setup
0. Check whether you GPU has [Compute Capability 3.0 or higher](https://developer.nvidia.com/cuda-gpus). If not, please refer how to install `TensorFlow` for CPU in `install_tensorflow_on_windows_os_cpu_gpu_python3.5_v2.pptx`
1. Download and install [CUDA® Toolkit 8.0](https://developer.nvidia.com/cuda-downloads)
2. Download [cuDNN v5.1](https://developer.nvidia.com/cudnn), extract downloaded file, copy `bin`, `include`, and `lib` folders to `%ProgramFiles%\NVIDIA GPU Computing Toolkit\CUDA\v8.0`
3. You should restart your computer to apply system’s changes
4. Download and install [Anaconda 4.2.0 with Python 3.5](https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe)
5. Open Command Prompt as Administrator
6. Install `TensorFlow` by entering `pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.1-cp35-cp35m-win_amd64.whl`
7. Enter `conda install -c conda-forge keras` to install Keras

## Usage
1. Download `cnn_mnist.ipynb`, `mlp_mnist.ipynb`, and `mnist_cnn_lstm_training.ipynb` to your computer. For example, `D:\dl`
2. Open Command Prompt, type `cd D:\dl`
3. Enter `jupyter notebook`
4. `Jupyter IDE` will be opened in a web browser, open one of the downloaded programs
5. Select menu `Cell` > `Run All` to run the program