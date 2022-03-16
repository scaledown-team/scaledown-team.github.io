# scaledown.distillation.KnowledgeDistillation

*class* scaledown.quantization.**KnowledgeDistillation**(teacher, student, optimizer, distillation\_loss, student\_loss, metric, activation, temperature=1)

### Parameters
- **teacher**: model  
  Specify the teacher model you want to perform distillation with. Should be a trained model.
- **student**: model  
  Specify the student model you want to distill the knowledge to.
- **optimizer**: tf or pytorch optimizer
  The optimizer you want to use to perform distillation
- **distillation\_loss**: tf or pytorch loss
  The loss function you want to use to perform distillation
- **student\_loss**: tf or pytorch loss
  The loss function you want to evaluate the student model with
- **metric**: tf or pytorch metric
  The metric you want to use to evaluate your model with
- **activation**: tf or pytorch activation
  The activation function you want to use at the end of your student model. This is not needed if an activation is already specified
- **temperature**: int
  The temperature to use while performing distillation

### Methods
- **train_step(data)**: Takes a training step for the data provided.
