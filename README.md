# Super Resolution in Tensorflow 2
In this repository I will implement SR papers using tensorflow 2.0


## SRCNN
I have trained the SRCNN for 60000 epochs.

You can find the trained models and training logs in this [link](https://drive.google.com/open?id=15BDCxku5RXoLUwUpvxT7f7do3lR453SG)

you can donwload the 91 dataset as well as Set5 and set14 in this [link](https://drive.google.com/open?id=1KTRWi8aIBSip0Ir7XvWjNg9eumhQan_R)

output:
*Ground truth* | *Low resolution x3* | *SRCNN output*
:---: | :---: | :---: 
<img src = 'outputs/SRCNN/hr.jpg'> | <img src = 'outputs/SRCNN/lr.jpg'> | <img src = 'outputs/SRCNN/sr.jpg'> 


*Train loss* | *Train psnr*
:---: | :---: 
<img src = 'outputs/SRCNN/train_loss.png'> | <img src = 'outputs/SRCNN/train_psnr.png'> 


*Valid loss* | *Valid psnr*
:---: | :---: 
<img src = 'outputs/SRCNN/valid_loss.png'> | <img src = 'outputs/SRCNN/valid_psnr.png'> 



## VDSR
You can find the trained models and training logs in this [link](https://drive.google.com/open?id=1VTLcCX9He7l3xnBzPjngMLjt3O39_QFm)

*Ground truth* | *Low resolution x3* | *VDSR output*
:---: | :---: | :---: 
<img src = 'outputs/VDSR/hr_vdsr.png'> | <img src = 'outputs/VDSR/lr_vdsr.png'> | <img src = 'outputs/VDSR/sr_vdsr.png'> 

*Loss* | *Psnr*
:---: | :---: 
<img src = 'outputs/VDSR/Loss.png'> | <img src = 'outputs/VDSR/psnr.png'> 
