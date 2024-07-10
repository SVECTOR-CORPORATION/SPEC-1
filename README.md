<div align="center">
  <h1>SPEC-1: Large Language Model (LLM) by SVECTOR</h1>
  <img src="SPEC_1.jpg" alt="SPEC-1" width="400">
</div>

SPEC-1 is a powerful Large Language Model (LLM) developed by SVECTOR Corporation in Gujarat, India. It is designed to enhance various AI-driven applications with its advanced generative capabilities.

## Overview

SPEC-1 features include:

- **Origin**: Developed in Gujarat, India by SVECTOR Corporation.
- **Parameters**: 3.5 billion parameters, providing substantial computational power.
- **Tokenization**: Supports a vocabulary size of 350K tokens, enhancing linguistic diversity.
- **Open Source**: Available for public use and contributions, fostering community-driven innovation.
- **Generative AI Capabilities**: Enables sophisticated text generation, conversation modeling, and more.
- **Efficiency**: Optimized for performance across diverse AI applications.

## Comparison with Latest Models

SPEC-1 competes favorably with contemporary large language models:

- **Performance**: Achieves superior results in text generation and natural language understanding tasks.
- **Accessibility**: Its open-source nature promotes transparency and accessibility in AI development.
- **Community Support**: Benefits from global contributions and continuous improvements.

## Future Development: SPEC2

SVECTOR is actively developing SPEC2, the successor to SPEC-1. While SPEC-1 remains open-source, SPEC2 will introduce proprietary advancements to further enhance AI capabilities.

## Installation

To integrate SPEC-1 into your project:

1. **Download SPEC-1 GGUF File**:
   Visit [models.svector.co.in](https://models.svector.co.in) to download the SPEC-1 GGUF model file.
   
2. **Run SPEC-1**: Follow installation instructions provided with the download to set up and run SPEC-1 on your local environment or using Ollama like services.

 [OR]

3. **Install and Run SPEC-1**:
   Follow these instructions to install and run SPEC-1 using the GGUF file:

   ```sh
   # Clone the repository
   git clone https://github.com/SVECTOR-CORPORATION/spec-1.git
   cd spec-1

   # Install dependencies
   pip install -r requirements.txt

   # Load and use the model in your application
   from spec1 import SPEC1Model

   # Specify the path to the GGUF file
   gguf_file_path = 'path/to/spec-1-model.gguf'

   model = SPEC1Model(gguf_file_path)
   output = model.generate_text(prompt="Example prompt", max_length=50)

---

Explore the potential of SPEC-1 for your AI applications and stay tuned for updates on SPEC2 development.

To integrate SPEC-1 into your project, follow these steps:

---

For inquiries or support related to SPEC-1, please contact:

- Email: [support@svector.co.in]

Visit [SVECTOR Corporation](https://www.svector.co.in) for more information about our AI initiatives.

© [2024] SVECTOR Corporation. All rights reserved.
