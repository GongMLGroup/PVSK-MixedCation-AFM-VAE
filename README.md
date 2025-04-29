# PVSK-MixedCation-AFM-VAE

This is a small collection of notebooks by **Yongtao Liu** and **Jiawei Gong** used to analyze atomic force microscopy (AFM) data for mixed-cation perovskite (PVSK) using variational autoencoders (VAEs).

---

## Notebooks

- `ToJiawei_SciFiReader.ipynb` ([preview](./ToJiawei_SciFiReader.ipynb))
    - Test of the SciFiReader package for loading AFM images. (Gong)
- `PVSK_Topo_grainsampling_to_Jiawei_SciFiReader.ipynb` ([preview](./PVSK_Topo_grainsampling_to_Jiawei_SciFiReader.ipynb))
    - Detection of grains in AFM images for sampling in Machine Learning applications (Liu)
- `imspec2_v3a_IV_Jiawei.ipynb` ([preview](./imspec2_v3a_IV_Jiawei.ipynb))
    - Joint image/spec VAE with latent space 'alignment' (cosine loss + linear map) & rotation/translation-invariant image VAE for perovskite IV analysis (Liu & Gong).
- `PerovskiteDataset.ipynb` ([preview](./PerovskiteDataset.ipynb))
    - Visualization of Process Cycle Efficiency (PCE), open circuit voltage (Voc), short circuit current density (JSC) and fill factor (FF) from the Perovskite Database. (Liu)