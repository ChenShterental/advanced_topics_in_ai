# Dog Breed Identification Using Deep Learning (Reproduction Project)

This project reproduces and adapts the methodology from the paper  
**"Dog Breed Identification Using Deep Learning"** (SISY 2018 – Ráduly et al.) using modern tools in PyTorch.

It uses **transfer learning** with two pretrained models — **Inception-V3** and **MnasNet-A1.3** — to classify 120 dog breeds from the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/).  
The notebook includes preprocessing, data augmentation, model fine-tuning, and evaluation using top-1 accuracy.

---

## Tools & Technologies
- Python, PyTorch, torchvision
- Inception-V3 and MnasNet-A1.3 (from `torchvision.models`)
- Stanford Dogs Dataset
- Jupyter Notebook

---

## Project Structure
- `dogs_breed_identification_pytorch_inception_v3.ipynb` – notebook for Inception-V3 model
- `dogs_breed_identification_pytorch_mnasnet_a_1_3.ipynb` – notebook for MnasNet-A1.3 model
- `LICENSE.txt` – license and usage terms
- `README.md` – project description and instructions

---

## License

This project is licensed under the  
**Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

You are free to use, share, and adapt the material for **non-commercial purposes**, as long as proper attribution is given.  
To view the full license, visit:  
[https://creativecommons.org/licenses/by-nc/4.0/legalcode](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

© 2025 Chen Sh. Licensed under CC BY-NC 4.0.

> **Note**: The dataset used (Stanford Dogs) is subject to its own non-commercial licensing terms via [ImageNet](http://www.image-net.org/download-images).

---

## How to Run
1. Clone the repository
2. Install required packages:  
   `pip install torch torchvision matplotlib`
3. Open either notebook in Jupyter or Colab:
   - `dogs_breed_identification_pytorch_inception_v3.ipynb`
   - `dogs_breed_identification_pytorch_mnasnet_a_1_3.ipynb`
   The dataset will be downloaded automatically when the notebook runs.

---

## Contact
For questions or collaboration opportunities, feel free to reach out!