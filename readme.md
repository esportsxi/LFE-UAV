# LFE-YOLO
# UAV Detection Method Based on Lightweight Feature Fusion and Enhancement

### Code Description
Our paper is currently in the review stage, and all paper codes will be made public after the paper is published.

The dataset DFA-YOLO UAV detection dataset contains 10403 images for training, 2798 images for validation, and 3086 images for testing, with a total of 16287 images.

The dataset demo has been uploaded.

### Code usage instructions
- Replace your own dataset and modify hyperparameters in the *args.py*
Modify the training dataset address
```
train_ir = ''
train_vi = ''
```
Modify the saving path of the model and loss
```
save_model_dir = ''
save_loss_dir = ''
```
Modify the  path of test model and test imgs dir
```
test_model_name = ''
test_imgs_dir= ''
```
train
```python
run main.py flag = 1
```
test
```
run main.py flag = 0
```

- We are currently developing a dataset of infrared and visible light drone images, which will be open sourced to the community in the future. Scholars are welcome to stay tuned