


## <div align="center"> Any2Captio: Interpreting Any Condition to Caption for Controllable Video Generation<div>



## Abstract

Scene graph (SG) representations can neatly and efficiently describe scene semantics, which has driven sustained intensive research in SG generation.
In the real world, multiple modalities often coexist, with different types, such as images, text, video, and 3D data, expressing distinct characteristics.
Unfortunately, current SG research is largely confined to single-modality scene modeling, preventing the full utilization of the complementary strengths of different modality SG representations in depicting holistic scene semantics.
To this end, we introduce Universal SG (USG), a novel representation capable of fully characterizing comprehensive semantic scenes from any given combination of modality inputs, encompassing modality-invariant and modality-specific scenes.
Further, we tailor a niche-targeting USG parser, USG-Par, which effectively addresses two key bottlenecks of cross-modal object alignment and out-of-domain challenges.
We design the USG-Par with modular architecture for end-to-end USG generation, in which we devise an object associator to relieve the modality gap for cross-modal object alignment.
Further, we propose a text-centric scene contrasting learning mechanism to mitigate domain imbalances by aligning multimodal objects and relations with textual SGs. 
Through extensive experiments, we demonstrate that USG offers a stronger capability for expressing scene semantics than standalone SGs, and also that our USG-Par achieves higher efficacy and performance.

<!-- <img src="./assets/full-usg3-crop.png" align="center" width="100%"> -->


 ![framework](./assets/intro.png)



## Code
Stay Tuned.




## Citation

If you find Any2Caotion is useful and use it in your project, please kindly cite:
```
@inproceedings{wu2025Any2Caption,
    title={Any2Caption: Interpreting Any Condition to Caption for Controllable Video Generation},
    author={Shengqiong Wu and Weicai Ye and Jiahao Wang and Quande Liu and Xintao Wang and Pengfei Wan and Di Zhang and Kun Gai and Shuicheng Yan and Hao Fei and Tat-Seng Chua2},
    booktitle={arxiv},
    year={2025}
}
```


