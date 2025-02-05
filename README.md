## Using LLMs with web-interfaces on Colab

Easy-to-follow setup for running LLM models with Ollama using web interfaces like OpenWebUI and Gradio with Colab. Gradio offers a public link for easy access, while OpenWebUI requires Ngrok to expose the URL. This offers advantages over local setups, including to use powerful GPUs and no local storage requirements. For best results, it is recommended to use Colab Pro+

### Usage
For OpenWeb UI with ngrok--> [LLM_model_with_OpenWebUI](https://github.com/karagol-taner/ollama-web-interfaces-with-colab/blob/main/LLM_model_with_OpenWebUI.ipynb)

For Gradio --> [LLM_model_with_Gradio](https://github.com/karagol-taner/ollama-web-interfaces-with-colab/blob/main/LLM_model_with_Gradio.ipynb)

### Key Features

- OpenWebUI Interface: Requires Ngrok to expose a secure URL for accessing the interface.
- Gradio Interface: Provides a public link for simple and seamless access to LLM models.
- Colab Connection: Avoid the complexities of local machine setups by utilizing Colab’s easy-to-use interface.
- Docker-Free Environment: Due to Docker's unavailability in Colab, we opted for a lightweight pip-based setup for package installation and environment management. Bypassed the Docker requirement by directly installing essential packages using pip.

### License

This project is available under the MIT license.
