# tech_swiss_knife



#### Check CUDA/GPU devices with tensorflow and cuda
```
python -c "import tensorflow as tf; tf.config.list_physical_devices('GPU')"
```
#### Enable/Disable GPU devices
```
export CUDA_VISIBLE_DEVICES='-1' # To enable, set it to 0
```
