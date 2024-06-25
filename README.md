# DenseNucleiDet

The Code for "Position-based anchor optimization for point supervised dense nuclei detection"

## Requirements

- Linux (Windows is not officially supported)
- Python 3.5+ (Python 2 is not supported)
- PyTorch 1.1 or higher
- CUDA 9.0 or higher
- NCCL 2
- GCC(G++) 4.9 or higher
- mmcv

## Train a dataset in COCO format

```bash
./tools/dist_train.sh ${CONFIG_FILE} ${GPU_NUM} [optional arguments]
```

## Test a dataset in COCO format

```bash
./tools/dist_test.sh ${CONFIG_FILE} ${CHECKPOINT_FILE} ${GPU_NUM} [--out ${RESULT_FILE}] [--eval ${EVAL_METRICS}]
```

---

## Citation

Please consider citing our paper in your publications if the project helps your research.

```
@article{yao2024position,
  title={Position-based anchor optimization for point supervised dense nuclei detection},
  author={Yao, Jieru and Han, Longfei and Guo, Guangyu and Zheng, Zhaohui and Cong, Runmin and Huang, Xiankai and Ding, Jin and Yang, Kaihui and Zhang, Dingwen and Han, Junwei},
  journal={Neural Networks},
  volume={171},
  pages={159--170},
  year={2024},
  publisher={Elsevier}
}
``` 

