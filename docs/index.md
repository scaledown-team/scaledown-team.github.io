# Scaledown
Scaledown is an Open-Source Neural Network Optimization Framework for TinyML Devices.

Simply put, we help you scaledown your large neural networks into small ones so that you can deploy them to resource constrained edge computing devices like Arduino's, Raspberry Pi's and Mobile Phones.

If you are wondering what TinyML or Edge Computing is, take a look at our [free book and course](https://scaledown-team.github.io/practical_tinyml_book/).


## Here is what we offer:



### Optimsation Techniques
Currently we offer serveral optimisation techniques for TinyML. We also offer a wide range of techniques which can help you in your applications.

| Type of Optimisation   	| Tensorflow         	| OpenVino                  	| PyTorch     	| NVIDIA TensorRT         	|
|------------------------	|--------------------	|---------------------------	|-------------	|-------------------------	|
| Quantization           	| &check; 	| In Progress               	| In Progress 	| Will be available soon! 	|
| Knowledge Distillation 	| &check;	| &cross;<sup>*</sup> 	| In Progress 	| Will be available soon! 	|
| Pruning                	| In Progress        	| &cross;<sup>*</sup>	| In Progress 	| Will be available soon! 	|

"*" = This Optimisation technique is not supported by the frameworks. In case, you find this information misleading, feel free to raise an [issue on Github](https://github.com/scaledown-team) 

 

### Conversion of Models between Frameworks

Alongside that, we also offer conversion between frameworks. So in case, you want to work across different devices supporting different frameworks, this wraper can help convert those models for you.

| From            	|  To Tensorflow          	|  To OpenVino            	| To PyTorch              	| ONXX                    	| To NVIDIA TensorRT      	|
|-----------------	|-------------------------	|-------------------------	|-------------------------	|-------------------------	|-------------------------	|
| Tensorflow      	| &cross;<sup>*<sup>    	| In Progress             	| In Progress             	| &check;                 	| Will be available soon! 	|
| OpenVino        	| In Progress     	| &cross;<sup>*</sup>     	| In Progress     	| In Progress             	| Will be available soon! 	|
| PyTorch         	| &check;                 	| In Progress             	| &cross;<sup>*</sup>     	| &check;                 	| Will be available soon! 	|
| ONNX 	| &check;	| &cross;<sup>*</sup> | &cross;<sup>*</sup>	| &cross;<sup>*</sup>	| Will be available soon!     	|