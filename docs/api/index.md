# API Reference

This is the reference for all the classes and functions available in ScaleDown. We also have a [User Guide](../guide/index.md) that contains technical information and implementation details about the algorithms available as a part of this framework. If you want to learn more about TinyML and how it works, check out our [free books and videos](https://github.com/scaledown-team/study-group).

## [`scaledown.load_model`](load_model.md): Loading Models
Utilities for loading supported models to scaledown. This is usually the first step that you need to do when working with scaledown. Once the models are loaded, you can then optimize them, benchmark their performance and then deploy them to different devices.

For more information on how to load models and get started with ScaleDown, check out our [User Guide](docs/guide/index.md).

**[scaledown.load_model(model, model_type)](docs/api/load_model.md)**:  Wrapper function for loading supported models

## [scaledown.quantization](quantization.md): Quantizing Models
Utilities for optimizing models uing quantizing. 

**User Guide**: See [Quantization](../guide/quantization.md) to learn more about the supported quantization algorithms and how they work 

**[`quantization.WeightQuantization`](weight_quantization.md)**: Perform only weight quantization of models. Good for reducing model size with less drop in accuracy.

**[`quantization.ActivationQuantization`](activation_quantization.md)**:
Perform weight and activation quantization of models. Good for reducing model size and for using `INT8` operations for executing models.


## [scaledown.distillation](distillation.md): Distilling Large Models
Utilities for distilling the knowledge of large models to smaller ones.

**User Guide**: See [Distillation](../guide/distillation.md) to learn more about the supported knowledge distillation algorithms and how they work 

**[`distillation.KnowledgeDistillation`](weight_quantization.md)**: Distill models using the original knowledge distillation technique proposed by Hinton et. al. Supports add temperature to distillation as well.
