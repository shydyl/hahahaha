# More visualization results for KAE
In order to verify the effectiveness of the model, we conduct experiments on datasets other than FFHQ.
## Results on Church pre-train
### Church to Haunted House
![img](https://github.com/shydyl/hahahaha/blob/main/C2H.png "FFHQ2Modigliani")


## Some additional experiments for KAE
### Generate Gradient Process
We set $\tau$ as 20 training the model and set $\tau$ from 0 to 20 \(total 21\) generating images. We show experimental results for different $\tau$ \(from samll to big\).  
![img](https://github.com/shydyl/hahahaha/blob/main/FFHQ2Modigliani.gif "FFHQ2Modigliani")

### Adapt to double target domain
We modify Eq 5 and 6 as follows：  
<div align=center>
<img src="https://github.com/shydyl/hahahaha/blob/main/eq5.png" width="180" height="70">
</div>

<div align=center>
<img src="https://github.com/shydyl/hahahaha/blob/main/eq6.png" width="280" height="20">
</div>

We mix double domain and the results as shown below:
![img](https://github.com/shydyl/hahahaha/blob/main/mix_meta_baby.png "mix_meta_baby")
