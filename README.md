## The official pytorch implement of "LLaVA-SP: Enhancing Visual Representation with Visual Spatial Tokens for MLLMs" [[Paper](https://arxiv.org/abs/2507.00505)]

The implementation changes of LLaVA-SP are in **llava_arch.py, clip_encoder.py, llava_trainer.py** and **train.py**.


## Install

Please see instructions for https://github.com/haotian-liu/LLaVA/



## LLaVA-SP Weights
Please check out https://huggingface.co/Levideus/models for all public LLaVA-SP checkpoints.

## Quick Start  
```
python llava/eval/run_llava.py
--model_path /path/llava-sp-cropping-lora
--model_base /path/vicuna-1.5-7b
```

## Citation

If you find LLaVA-SP useful for your research and applications, please cite using this BibTeX:
```bibtex
@InProceedings{Lou_2025_ICCV,
    author    = {Lou, Haoran and Fan, Chunxiao and Liu, Ziyan and Wu, Yuexin and Wang, Xinliang},
    title     = {LLaVA-SP: Enhancing Visual Representation with Visual Spatial Tokens for MLLMs},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2025},
    pages     = {22014-22024}
}
```
