# CLAY Dataset
The dataset includes UI object type labels (e.g., BUTTON, IMAGE, CHECKBOX) that describes the semantic type of an UI object on Android app screenshots. It is used for training and evaluation of the screen layout denoising models (paper will be linked soon).

clay_labels.csv contains all the type labels for the UI objects.

label_map.txt contains mapping from the type id to the type string. The ROOT type is assigned to the root node of each view hierarchy.

split_*_id.txt contains the train/dev/test split of the screen ids used by the paper for model training and evaluation.
