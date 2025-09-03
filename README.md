# Nine Thousand Models 🤖

This repository contains model configuration files for parts prediction models. Each JSON file defines the data sources, hyperparameters, and deployment configuration for machine learning models that predict component behavior.

Each model configuration includes DVC data sources, Kubeflow pipeline specifications, and model hyperparameters.

## 🚀 Onboarding New Part Prediction Models

To onboard a new part prediction model, simply:

1. 📝 Create a JSON file with your model name and necessary configuration information
2. 🎯 [The model training pipeline](https://github.com/nine-thousand-models/nine-thousand-pipeline/blob/main/templates/pipelines/model-pipeline.yaml) will automatically handle the rest!
3. You'll find the model deployed in `test` environment through an entry in [GitOps repository](https://github.com/nine-thousand-models/nine-thousand-models-gitops)

That's it! ✨ The automated pipeline takes care of all the deployment and orchestration for you.
