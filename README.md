# Label smoothing with uniform gaussian noise



```bash
python train_label_smoothing.py --data_dir [PATH/TO/appa-real-release] --tensorboard tf_log --noise_std = [standard deviation of the noise]
```

# Label smoothing with gaussian noise depending on the label values

```bash
python train_label_smoothing_affine.py --data_dir [PATH/TO/appa-real-release] --tensorboard tf_log --noise_min = [standard deviation of the noise at age 0] --noise_max = [standard deviation of the noise at age 100]
```
