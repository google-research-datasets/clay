# CLAY Dataset

Please cite our paper if you use the dataset:

```
@InProceedings{clay,
  title     = "Learning to Denoise Raw Mobile UI Layouts for Improving Datasets at Scale",
  booktitle = "Proceedings of the 2022 {CHI} Conference on Human Factors in
               Computing Systems",
  author    = "Li, Gang and Baechler, Gilles and Tragut, Manuel and Li, Yang",
  publisher = "Association for Computing Machinery",
  pages     = "1--13",
  month     =  may,
  year      =  2022,
  address   = "New Orleans, LA, USA",
  url = {https://doi.org/10.1145/3491102.3502042}
}
```

The dataset includes UI object type labels (e.g., BUTTON, IMAGE, CHECKBOX) that describes the semantic type of an UI object on Android app screenshots. It is used for training and evaluation of the screen layout denoising models (paper will be linked soon).

clay_labels.csv contains all the type labels for the UI objects.

label_map.txt contains mapping from the type id to the type string. The ROOT type is assigned to the root node of each view hierarchy.

split_*_id.txt contains the train/dev/test split of the screen ids used by the paper for model training and evaluation.
