# GPT 4 Vision preview
As can be read in the [Azure OpenAI - Whats new of December 2023](https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new#gpt-4-turbo-with-vision-now-available) GPT-4 with Vision preview is out in public preview. I created a resource in the Azure region: `SwitzerlandNorth` since thats the only region next to `West US` that are able to host the GPT-4 Vision preview models.

One has to create a model deployment inside the Azure OpenAI service from a `gpt-4` model with verison `vision-preview`. If its not enlisted in the available models you either do not have preview access or you have created an Azure OpenAI service within the wrong region. Check here for model availability:
https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models#gpt-4-and-gpt-4-turbo-preview-model-availability

# API Calls
Sample API calls can be found here, make sure to use the latest API version.
https://learn.microsoft.com/en-us/azure/ai-services/openai/reference#chat-completions
