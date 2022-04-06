# ScaleDown
ScaleDown is an Open-Source Neural Network Optimization Framework for TinyML Devices.

Simply put, we help you scaledown your large neural networks into small ones so that you can deploy them to resource constrained edge computing devices like Arduino's, Raspberry Pi's and Mobile Phones.

If you are wondering what TinyML or Edge Computing is, take a look at our [free course](https://github.com/scaledown-team/study-group)


## Features
Broadly to run models on TinyML devices, you need to be able to do the following:
- **Optimize** your model using algorithms like quantization, pruning, knowledge distillation etc.,
- **Benchmark** and **Evaluate** your model's performance, and,
- **Deploy** your model to the TinyML device.

These are the three verticals that ScaleDown takes care of so that you can focus on the main task of getting data and training models for interesting applications!

In addition to the above, we also aim to be framework agnostic so you can use our algorithms no matter what deep learning library you used to train your model. We do this by having APIs for **model conversion** from your framework to whichever framework supports the algorithm you want to optimize your model with.

Finally, we know how it can be difficult to properly optimize your models for edge devices, so we will also provide API for **automated model optimization** based on your hardware restrictions.

### Optimization Techniques
Currently we offer serveral optimization techniques for TinyML. We also offer a wide range of techniques which can help you in your applications.

| Type of Optimisation   	| Tensorflow         	| OpenVino                  	| PyTorch     	| NVIDIA TensorRT         	|
|------------------------	|--------------------	|---------------------------	|-------------	|-------------------------	|
| Quantization           	| &check; 	| In Progress               	| In Progress 	| Will be available soon! 	|
| Knowledge Distillation 	| &check;	| &cross;<sup>*</sup> 	|  &check; 	| Will be available soon! 	|
| Pruning                	| In Progress        	| &cross;<sup>*</sup>	| In Progress 	| Will be available soon! 	|


### Conversion of Models between Frameworks

Alongside that, we also offer conversion between frameworks. So in case, you want to work across different devices supporting different frameworks, this wrapper can help convert those models for you.

| From            	|  To Tensorflow          	|  To OpenVino            	| To PyTorch              	| ONXX                    	| To NVIDIA TensorRT      	|
|-----------------	|-------------------------	|-------------------------	|-------------------------	|-------------------------	|-------------------------	|
| Tensorflow      	| &cross;<sup>*<sup>    	| In Progress             	| &cross;<sup>*</sup>             	| &check;                 	| Will be available soon! 	|
| OpenVino        	| In Progress     	| &cross;<sup>*</sup>     	| In Progress     	| In Progress             	| Will be available soon! 	|
| PyTorch         	| &check;                 	| In Progress             	| &cross;<sup>*</sup>     	| &check;                 	| Will be available soon! 	|
| ONNX 	| &check;	| In Progress | In Progress| &cross;<sup>*</sup>	| Will be available soon!     	|


"*" = This Optimisation technique is not supported by the frameworks. In case, you find this information misleading, feel free to raise an [issue on Github](https://github.com/scaledown-team) 

## Contact Us
ScaleDown is currently in active development. In case you run into any issues, feel free to raise an [issue on Github](https://github.com/scaledown-team).

You can also contact us via email at `scaledown.tinyml@gmail.com`
