### DeepSkeleton
object skeleton extraction in a nature image.

Code for our [CVPR2016](http://cvpr2016.thecvf.com/) paper "**Object Skeleton
Extraction in Natural Images by Fusing Scale-associated Deep Side Outputs**" and TIP paper "**DeepSkeleton: Learning Multi-task Scale-associated Deep Side Outputs for Object Skeleton Extraction in Natural Images**".

![](http://7xn7wz.com1.z0.glb.clouddn.com/DeepSkeleton.png?imageView2/2/w/500)
#### Requirement:
**For test:**
* [our pretrained model on SK506 dataset](http://data-10045577.cos.myqcloud.com/caffe-models/sk-cvpr/sk506_it14k.caffemodel)
    
  or

* [our pretrained model on Horse dataset](http://data-10045577.cos.myqcloud.com/caffe-models/sk-cvpr/horse_it14k.caffemodel)

**For train:**
* Finetune model [*vgg-16*](http://7xocv2.dl1.z0.glb.clouddn.com/5stage-vgg.caffemodel)

* Our new dataset [*SK506*](http://7xocv2.dl1.z0.glb.clouddn.com/sk506.tar.gz)

### New dataset
We release our new larger dataset on Object Skeleton [SK-LARGE](http://zhaok.xyz/sk-large).

Code base on [*caffe*](http://caffe.berkeleyvision.org/)

___
For more technical details and information about the code & dataset please visit the [project page](http://zhaok.xyz/deepsk).

