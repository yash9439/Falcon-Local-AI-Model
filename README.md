## Installation

To install the required dependencies, run the following command:

```shell
!pip install -q transformers einops accelerate langchain bitsandbytes
```

# Falcon Local

This repository contains three versions of the Falcon code, each designed for different use cases. These versions utilize different libraries and models for text generation. Below is a brief description of each version:

<br>

## Version 1 : Using Transformers only.

**File**: `falcon_local_withoutHuggingFacePipeline.py`

This version uses the `transformers` library and the `tiiuae/falcon-7b-instruct` model. Its a text-generation model which gives answer for the question asked.

<br>

## Version 2 : Using Transformers and HuggingFacePipeline only.

**File**: `falcon_local_withHuggingFacePipeline.py`

The second version of the Falcon code utilizes the `langchain` library and the `tiiuae/falcon-7b-instruct` model. It employs the `HuggingFacePipeline` class for text generation and generates a response to a given question.

<br>

## Version 3 : Using HuggingFacePipeline Only.

**File**: `falcon_local_HuggingFaceInferenceAPI.py`

In this version, the code incorporates the `dotenv`, `langchain`, and `textwrap` libraries. It uses the HuggingFace model hub and the `tiiuae/falcon-7b-instruct` model. The code demonstrates a summarization chain for generating responses to questions.

<br>

Please refer to the individual code files for more details and instructions on running each version of the Falcon code.

<br>

## License

This project is licensed under the [Apache License 2.0](LICENSE).