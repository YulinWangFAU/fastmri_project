# FastMRI Undersampled k-space Reconstruction

**Project Title**: Full k-space prediction and reconstruction using under-sampled k-space to reduce scan time.

## 🧠 Objective
This project aims to reconstruct fully-sampled MR images from under-sampled k-space data using deep learning techniques (e.g., CNN, U-Net, or nnU-Net). The focus is on:

- Undersampling strategies in k-space
- Image reconstruction pipeline via IFFT and neural networks
- Data consistency enforcement
- Testing multiple architectures on FastMRI data

## 📁 Project Structure

```
fastmri_project/
├── data/           # Raw and preprocessed data
├── notebooks/      # Jupyter notebooks for visualization and testing
├── src/            # Source code (model, utils, etc.)
├── results/        # Output reconstructions, logs, images
├── .gitignore
├── README.md
└── requirements.txt
```


## 🗃️ Dataset
We use the [fastMRI](https://fastmri.org/) dataset. Currently working with:
- `brain_multicoil_train_batch_0.tar.xz`

## 🔧 To-Do
- [x] Setup Git and folder structure
- [ ] Decompress data and explore `.h5` content
- [ ] Implement k-space undersampling
- [ ] Build a PyTorch model with IFFT and training loop
- [ ] Add data consistency layer
- [ ] Train with nnUNet or custom CNN

## 📌 Requirements
See `requirements.txt` for needed packages.
