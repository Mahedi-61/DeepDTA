# About DeepDTA: deep drug-target binding affinity prediction

The approach used in this work is the modeling of protein sequences and compound 1D representations with convolutional neural networks (CNNs).

![Figure](https://github.com/hkmztrk/DeepDTA/blob/master/docs/figures/deepdta.PNG|width=100)

# Installation

## Data

## Requirements

You'll need to install following in order to run the codes.

*  [Python 3.x](https://www.python.org/downloads/)
*  [Keras 2.x](https://pypi.org/project/Keras/)
*  [Tensorflow 1.x](https://www.tensorflow.org/install/)
*  numpy
*  matplotlib

You have to place "data" folder under "source" directory. 

# Usage
```
python run_experiments.py --num_windows 32 \
                          --seq_window_lengths 8 12 \
                          --smi_window_lengths 4 8 \
                          --batch_size 256 \
                          --num_epoch 100 \
                          --max_seq_len 1000 \
                          --max_smi_len 100 \
                          --dataset_path 'data/kiba/' \
                          --problem_type 1 \
                          --log_dir 'logs/'


```





**For citation:**
