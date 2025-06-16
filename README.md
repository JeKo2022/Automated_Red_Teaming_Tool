**Automated Red Teaming Tool**

This is an interactive red teaming tool that allows users to conduct red teaming of language models whether hosted locally or accessed via API, exposed through streamlit user interface. The goal is to enable users to enhance the safety of their systems. 

### This project showcases:
- Full-stack **AI safety engineering** skills, including:
  - Front-end tool development with Streamlit
  - Backend orchestration of LLMs for evaluation
  - Prompt management and LLM-as-a-judge reasoning
  - Data handling and visualization of safety outcomes

Users can:
- Upload their own red teaming prompts
- Enter prompts manually
- Select from curated prompt sets (e.g., from academic literature, GitHub repositories)

The tool's key innovation lies in its **automated evaluation pipeline**: users specify a *target model* to be tested and a red teaming assistant that evaluates each response based on user specifications using an LLM-as-a-judge strategy. Results are visualized using:
- Clear **tables** i.e. showing harmful vs. harmless completions
- Intuitive **charts and overviews** to support qualitative and quantitative analysis

This makes it easy to:
- Detect safety successes and failures
- Compare behavior across models
- Share and interpret safety findings transparently

> ⚠️ This tool is under active development and best suited for evaluation research and red teaming experiments.

## Features

-  Supports local and API-based model access
-  Custom or preset prompt sets
-  Judge model (LLM-as-a-judge) evaluates responses
-  Visual output with summaries, tables, and plots
-  Easily extensible for different model configurations or prompt strategies

## 🖼️ Screenshot Automated Red Teaming Tool Screenshot

<img width="1497" alt="image" src="https://github.com/user-attachments/assets/48cd302c-5b28-4c96-98d6-1ded4fa9bdaa" />


## 🔒 Private Demo Video

A video demo of this tool is available for trusted reviewers.  
Please refer to the link provided to you by me. (i.e. in my resume or otherwise, contact me directly for access)

All rights reserved.

This repository is made available for viewing purposes only. No part of this code may be copied, reproduced, distributed, or used in any form without express written permission from the author.

