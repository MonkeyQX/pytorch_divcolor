# pytorch_divcolor

PyTorch implementation of Diverse Colorization -- Deshpande et al. "[Learning Diverse Image Colorization](https://arxiv.org/abs/1612.01958)"                 

Fetch data by

```
bash get_data.sh
```

Execute main.py to first train vae+mdn and then, generate results for LFW

```
python main.py lfw
```

If you use this code, please cite
                                                                                                    
```
@inproceedings{DeshpandeLDColor17,                                                                  
  author = {Aditya Deshpande, Jiajun Lu, Mao-Chuang Yeh, Min Jin Chong and David Forsyth},          
  title = {Learning Diverse Image Colorization},                                                    
  booktitle={Computer Vision and Pattern Recognition},                                              
  url={https://arxiv.org/abs/1612.01958},                                                           
  year={2017}                                                                                       
} 
```

Some examples of diverse colorizations on LFW

<p align='center'>
<img src='./images/pytorch_lfw.png' width=900 />
</p>

