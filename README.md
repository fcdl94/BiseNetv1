# MLDL 2021 Course
## BiseNet
Starting code for the student belonging to the project "Incremental Learning in semantic segmentation" <br>
BiSeNet based on pytorch 0.4.1 and python 3.6

## Dataset  
Download PascalVOC with the script in data/download.voc.
  
## Train
```
python train.py
```  

## Test
```
python test.py
```

On Colab:
```
!git clone https://github.com/fcdl94/BiseNetv1.git
%cd BiseNetv1
!data/download_voc.sh
```
Then you can use to run the scripts:
```
!python train.py
``` 
Remeber to enable the GPU runtime (Runtime -> Change Runtime Type -> GPU)
