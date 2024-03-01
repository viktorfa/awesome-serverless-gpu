# Awesome Serverless GPU

List of where to run code on GPUs for AI, inference, predictions that are serverless.  
Serverless is defined as pay-as-you-go, scale-to-zero, minimal infrastructure configuration.

Serverless GPU is a reletively new and fast evolving field. New services are appearing and disappearing frequently.  
I will do my best to keep the list updated, and soon include benchmarks.

Common weaknessses of serverless GPU at the moment is very long cold starts, and configuration that are less easy to use than the more mature field of serverless on CPUs.


## Inference

### Bring your own model
True serverless inference
- Inferless.com
- Replicate.com
- Runpod.io
- Modelz.ai
- Banana.dev (Shutting down March 31st 2024)
- Beam.cloud
- Mystic.ai
- Modal.com

### Predefined models
True serverless with a limited set of models
- Cloudflare AI
- OpenAI
- Mistral
- Sievedata.com
- Together.ai
- Anyscale.com
- Fireworks.ai

### Not serverless inference
Needs dedicated server, but works with your own model  
- Together.ai
- Sievedata.com
- Anyscale.com
- Run.io
- Huggingface.co
- Lepton.ai

### Dev on GPUs
Flexible on-demand GPU providers
- Brev.dev
- [Colab](https://colab.research.google.com/)
- Kaggle.com
