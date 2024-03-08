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
- Vast.ai
- Lambdalabs.com


## Dev on GPUs
Flexible on-demand GPU providers
- Brev.dev
- [Colab](https://colab.research.google.com/)
- Kaggle.com
- Modal.com
- Beam.cloud


## Predefined models over API

### Speech to text
- [OpenAI](https://platform.openai.com/docs/models/whisper)
- [Amazon](https://aws.amazon.com/transcribe/), [Azure](https://azure.microsoft.com/en-us/products/ai-services/speech-to-text), [Google](https://cloud.google.com/speech-to-text)
- Gladia.com
- Deepgram.com
- Speechmatics.com
- Sieve ASR

### Text to speech
- [OpenAI](https://platform.openai.com/docs/guides/text-to-speech)
- [Amazon](https://aws.amazon.com/polly/), [Azure](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/rest-text-to-speech), [Google](https://cloud.google.com/text-to-speech)
- [Speechify.com](https://speechify.com/)
- [Elevenlabs.io](https://elevenlabs.io/api)
- [Unrealspeech.com](https://unrealspeech.com/)
- [Play.ht](https://play.ht/)
- [Murf.ai](https://murf.ai/)

### Image generation
- [OpenAI Dall-e](https://platform.openai.com/docs/guides/images/introduction)
- [Dreamstudio](https://dreamstudio.com/api/)
- [Stablediffusionapi.com](https://stablediffusionapi.com/docs/)
- [Modelslab.com](https://docs.modelslab.com/image-editing/overview)

## Workflow platforms
- [Leap](https://www.tryleap.ai/)

## AI Agents for Websites
- [Chatflow](https://chatflow.no/)
- [OneAI](https://oneai.com/)
- [SiteGPT](https://sitegpt.ai/)
- [Chatbase](https://www.chatbase.co/)
