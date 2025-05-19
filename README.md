# ComputerVision_Geology
Application of Computer Vision in the field of Geology - reconstruction subsurface properties (full-waveform inversion problems).

Summary

Computer vision, powered by deep learning, has transformed numerous domains, including medical imaging, energy exploration, autonomous vehicles, and security. In the field of geology, computer vision techniques are increasingly applied to address complex geophysical challenges, such as reconstructing subsurface velocity models through full-waveform inversion (FWI). FWI is a computationally intensive method used to estimate subsurface properties (e.g., seismic velocity, density) by iteratively minimizing the difference between observed and modeled seismic waveforms. Traditional FWI approaches often struggle with non-linearities, high computational costs, and sensitivity to initial models. Deep learning-based computer vision techniques, such as convolutional neural networks (CNNs) and generative adversarial networks (GANs), offer promising solutions by enhancing the accuracy and efficiency of subsurface imaging.

This repository serves as a comprehensive archive of recent advancements in deep learning models for FWI, covering published works up to 2025. It also includes novel models I have developed, tailored specifically for geophysical applications. These models leverage _computer vision techniques_ to process seismic data, improve velocity model reconstruction, and address challenges like noise robustness and resolution enhancement. The repository aims to provide a pointer and also resources for expert and entusiasts in this field. The software is open source under  BSD-3 License license: 

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


__Packages__

The followingPython packages are used in the development and implementation of the models in this repository:
- PyTorch: A flexible deep learning framework used for building and training neural network models, particularly CNNs and GANs, for seismic data processing and velocity model reconstruction. Its dynamic computation graph and extensive library support make it ideal for rapid prototyping and deployment.
- Pandas: Utilized for efficient data manipulation and preprocessing of large seismic datasets, enabling streamlined handling of geophysical data formats.
- NumPy: Provides robust numerical computation capabilities for matrix operations, data transformations, and mathematical modeling essential for FWI algorithms.
- Matplotlib: Employed for visualizing seismic data, velocity models, and training performance metrics, facilitating the interpretation of results.
- timm (PyTorch Image Models): A library of pre-trained computer vision models, used to adapt state-of-the-art image processing architectures (e.g., ResNet, Vision Transformers) for seismic image reconstruction tasks.
- SciPy: Included for advanced scientific computations, such as signal processing and optimization, which are critical for preprocessing seismic data and refining FWI results.
- Seaborn: Enhances visualization capabilities with statistical plotting, used to create detailed and aesthetically clear representations of model outputs and comparisons.

---
Table of contents
- [Papers - Notes - References]()
- [Models]()
