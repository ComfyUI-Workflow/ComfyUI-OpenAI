# ComfyUI OpenAI Nodes

![Cover Image](cover.png)

### Installation and Usage

1. Navigate to ComfyUI/custom_nodes folder in terminal or command prompt.
2. Clone the repo using the following command:
   `git clone https://github.com/ComfyUI-Workflow/ComfyUI-OpenAI`
3. Go to `custom_nodes/ComfyUI-OpenAI` and install depedencies by running `pip install -r requirements.txt`
4. Restart ComfyUI

## Features(More to come)

### Image Captioning

This node uses OpenAI's vision models for image captioning. It lets you choose:

- **model**: Choose from a variety of OpenAI models
- **system_prompt**: Customize the system prompt to guide the AI's behavior
- **caption_prompt**: Specify a captioning prompt to focus the AI's description
- **max_tokens** and **temperature**: Fine-tune the output length and creativity
- **api_key**: Input your OpenAI API key for authentication

These parameters allow you to customize the captioning process to suit your specific needs and preferences. You can adjust the model selection, prompts, and generation settings to achieve the desired output for your image captioning tasks.

Key features:

- No need to run your own captioning infrastructure
- Flexible configuration options
- Seamless integration with ComfyUI workflows

Example use cases:

- Generating detailed descriptions of generated images
- Creating alt text for accessibility
- Analyzing visual content in various domains (e.g., medical, scientific, artistic)

By utilizing OpenAI's powerful vision models, this node enables you to incorporate state-of-the-art image understanding into your ComfyUI projects with minimal setup.
