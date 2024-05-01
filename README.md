# PuLID

### :open_book: PuLID: Pure and Lightning ID Customization via Contrastive Alignment
> [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2404.16022)<br>
> Zinan Guo*, Yanze Wu*✝, Zhuowei Chen, Lang Chen, Qian He <br>
> (*Equal Contribution, ✝Corresponding Author) <br>
> ByteDance Inc <br>

### :triangular_flag_on_post: Updates
* **2024.05.01**: release codes&models.
* **2024.04.25**: release arXiv paper.

## Examples
Images generated with our PuLID
![examples](https://github.com/ToTheBeginning/PuLID/assets/11482921/65610b0d-ba4f-4dc3-a74d-bd60f8f5ce37)
Applications

https://github.com/ToTheBeginning/PuLID/assets/11482921/9bdd0c8a-99e8-4eab-ab9e-39bf796cc6b8

## :wrench: Dependencies and Installation
- Python >= 3.7 (Recommend to use [Anaconda](https://www.anaconda.com/download/#linux) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- [PyTorch >= 2.0](https://pytorch.org/)
```bash
# clone PuLID repo
git clone https://github.com/ToTheBeginning/PuLID.git
cd PuLID
# create conda env
conda create --name pulid python=3.10
# activate env
conda activate pulid
# Install dependent packages
pip install -r requirements.txt
```

## :zap: Quick Inference
### Gradio Demo
```bash
python app.py
```


##  Citation
If PuLID is helpful, please help to ⭐ the repo.

If you find this project useful for your research, please consider citing our paper:
```bibtex
@article{guo2024pulid,
  title={PuLID: Pure and Lightning ID Customization via Contrastive Alignment},
  author={Guo, Zinan and Wu, Yanze and Chen, Zhuowei and Chen, Lang and He, Qian},
  journal={arXiv preprint arXiv:2404.16022},
  year={2024}
}
```

## :e-mail: Contact
If you have any comments or questions, please [open a new issue](https://github.com/ToTheBeginning/PuLID/issues/new/choose) or feel free to contact [Yanze Wu](https://tothebeginning.github.io/) and [Zinan Guo](mailto:guozinan.1@bytedance.com).