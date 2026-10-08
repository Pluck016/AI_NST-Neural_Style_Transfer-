# AI_NST (Neural Style Transfer)

A deep learning web application that merges the artistic style of one image with the content of another using PyTorch and Flask.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About the Project

**AI_NST** is an interactive web application powered by Convolutional Neural Networks (CNNs). By employing optimization techniques on intermediate activations of pretrained vision models (such as VGG19), it separates and recombines the structure of a content image with the stylistic attributes (textures, colors, brushstrokes) of a reference artwork.

### Key Features
* 🎨 **Style & Content Fusion:** Blends arbitrary content and style image pairs to create new visual artwork.
  
* ⚡ **PyTorch Integration:** Uses pretrained deep learning backbones for feature extraction and Gram matrix computation.

* 🌐 **Flask Web Interface:** Simple UI to upload images, adjust style/content weight ratios, and trigger processing.
  
* 🛠️ **Deployment Ready:** Configured for cloud hosting on platforms like Render.

---

## Built With

* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)
* [Torchvision](https://pytorch.org/vision/stable/index.html)
* [Flask](https://flask.palletsprojects.com/)
* [Pillow (PIL)](https://python-pillow.org/)
* [NumPy](https://numpy.org/)

---

## Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

* Python 3.8+
* `pip` package manager
* `git`
* *(Optional)* NVIDIA GPU with CUDA support for accelerated image optimization.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/Pluck016/AI_NST-Neural_Style_Transfer-.git](https://github.com/Pluck016/AI_NST-Neural_Style_Transfer-.git)
Navigate to the project directory:

Bash
cd AI_NST-Neural_Style_Transfer-

Create and activate a virtual environment:

Bash
python -m venv venv

# On Windows:
venv\Scripts\activate

Install the required dependencies:

Bash
pip install -r requirements.txt
Usage

Launch the local Flask server:

Bash
python app.py

Open your web browser and navigate to:

Plaintext
[http://127.0.0.1:5000](http://127.0.0.1:5000)

Upload a Content Image (e.g., a photograph) and a Style Image (e.g., a painting), then run the transfer pipeline to generate your stylized image.

Roadmap
[x] Basic project architecture and Flask interface


[x] PyTorch NST implementation using VGG feature extraction


[ ] Implement fast feed-forward Style Transfer models for real-time inference


[ ] Add real-time progress tracking/preview generation in the frontend


[ ] Optimize memory footprint for CPU/cloud deployments

Contributing
Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project


Create your Feature Branch (git checkout -b feature/AmazingFeature)


Commit your Changes (git commit -m 'Add some AmazingFeature')


Push to the Branch (git push origin feature/AmazingFeature)


Open a Pull Request

License

Distributed under the MIT License. See LICENSE for more information.

Contact

Pluck016 — GitHub Profile

Project Link: https://github.com/Pluck016/AI_NST-Neural_Style_Transfer-
