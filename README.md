# Title: SSP-MambaNet: An automated System for Detection and Counting of Missing Seedlings in Glass Greenhouse-Grown Detoxified Strawberry
# Details
### common.py: the code of model 
### flower_count.py: the code of loss
### commonv20_spdffa.yaml: the code for model construction
## Train
To train the gan model by yourself, please: 
1. Download the ```'dataset.zip'``` following the above ```Dataset``` section and unzip the ```"datasets/"``` to the root of this repo.
2. Check the configuration
3. Train the model by running:
    ```
    python train.py
    ```
## Test
To generate synthetic dataset on your own pc, simply check the arguments in test.py and run:
   ```
   python test.py
   ```
## Detection of seedling deficiency in nutrient pots
The main algorithm is in tool/detect_Missing_pot.py
## Data availability
>>The raw data, among the labels are available upon reasonable request to 18154346943@163.com or [this form](https://pan.baidu.com/s/1vybEP6-64aLG4I78nVipBw?pwd=mn9m  Extracted code：mn9m)

