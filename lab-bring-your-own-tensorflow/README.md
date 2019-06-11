# Bring your own TensorFlow

In this lab, you learn how to define your own custom machine learning model. The lab takes advantage of Amazon SageMaker's 
ability to let you bring your own TensorFlow training script. 
The script defines a simple neural network using Keras and TensorFlow, and the training is 
executed in a SageMaker-provided TensorFlow container. 
Hosting is provided by the same container using TensorFlow Serving.

The sample also demonstrates how to perform SageMaker automatic model tuning against a script mode trained TensorFlow model,
including impact to the definition of the neural network itself.

In the [setup lab](../lab-0-setup/README.md), you cloned the workshop GitHub repository. Navigate to the `lab-bring-your-own-tensorflow` folder in the workshop and open the provided Jupyter notebook. The notebook synthesizes a claims dataset and builds a logistic regression network to predict whether the claim represents a total loss.

Follow the instructions in the notebook to complete the lab. You will first set a USER_PREFIX based on your name or username. This will provide a prefix for your training job name and endpoint name, and will facilitate later on performing the auto scaling lab.
