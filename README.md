# Inverse Imaging Projects

Implementation notebooks developed during COMP0114 (2025–26):

- **Regularised deconvolution:** Gaussian forward models, GMRES/LSQR reconstruction, parameter selection, gradient regularisation and edge-aware weights.
- **Tomography and denoising:** ASTRA projection/backprojection and FBP, Tikhonov reconstruction, sinogram inpainting, wavelet thresholding and iterative shrinkage.

## Run

Use Python 3.12+ and install `requirements.txt`; the tomography notebook additionally needs `requirements-tomography.txt` and a compatible ASTRA installation. Start Jupyter in `notebooks/` and run cells in order.

`regularised_deconvolution.ipynb` uses an optional `test_image.jpg`, with a procedural fallback when that file is absent. For tomography, provide your own `SLphan.npy` phantom. Neither input images nor phantom datasets are distributed.

Some reconstruction steps construct dense operators and can be memory-intensive. The original numerical implementation is retained; no new reconstruction-accuracy claims are made by this export.

## Publication scope

This is a curated portfolio of coursework implementations from the author's local working files. Course questions, marking rubrics, slides, reports, student identifiers, notebook outputs, input datasets, trained weights and commercial models are not included. Original private archives remain separate.

Supply your own appropriately licensed inputs where required. Existing algorithm limitations are preserved; publication is not a claim of a new benchmark or a complete reproduction of the original assessment. Dependencies retain their own licences. No blanket licence is added to third-party material.
