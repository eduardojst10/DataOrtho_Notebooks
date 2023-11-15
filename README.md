# DataOrtho Notebooks
## Environment Setup

### Windows Setup (GeForce RTX 3090)

On a Windows system with a GeForce RTX 3090, follow these steps:

#### 1. **NVIDIA Driver**
   - Ensure the latest NVIDIA driver is installed for the RTX 3090. (Driver version: 537.42, DCH type)

#### 2. **CUDA Toolkit**
   - Install **CUDA 11.2**, compatible with the RTX 3090.

#### 3. **cuDNN**
   - Download and install **cuDNN v8.1.0** for CUDA 11.2. Make sure to place the cuDNN files in the correct CUDA Toolkit directories.

#### 4. **Python**
   - Use **Python 3.8** for compatibility with TensorFlow and other libraries.

#### 5. **Miniconda**
   - The environment created for the notebooks was Miniconda.

#### 6. **TensorFlow**
   - Install TensorFlow within the Conda environment, ensuring compatibility with CUDA 11.2 and cuDNN 8.1.0.

#### 7. **Additional Libraries**
   - Install necessary Python libraries such as NumPy, pandas, and Matplotlib in the Conda environment.

### Ubuntu Setup (NVIDIA GeForce 3080 Ti)

Using an NVIDIA GeForce 3080 Ti on Ubuntu, these were the guidelines:

#### 1. **NVIDIA Driver**
   - Install the NVIDIA driver appropriate for the GeForce 3080 Ti from the Ubuntu repositories or NVIDIA's website.

#### 2. **CUDA Toolkit**
   - Install **CUDA 10.1**, which is suitable for GeForce 3080 Ti.

#### 3. **cuDNN**
   - Download and set up **cuDNN version 7.6.5**, ensuring it matches with CUDA 10.1.

#### 4. **Python**
   - Opt for **Python version 3.7.5**.

#### 5. **Miniconda**
   - Like on Windows, Miniconda was used .

#### 6. **TensorFlow and Libraries**
   - Install TensorFlow, making sure it aligns with the installed CUDA and cuDNN versions.

*Refer to the official documentation of each component for detailed installation instructions and compatibility information. Adjust for your specifc OS and GPU*


Eduardo Teixeira, BiRDLAB
