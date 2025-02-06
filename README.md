# PP-OCRv4_OpenVINO

## Introduction
PP-OCRv4_OpenVINO is a demo project that demonstrates how to perform inference using the PP-OCRv4 model with OpenVINO. The PP-OCRv4 model is an advanced Optical Character Recognition (OCR) model that can recognize text in images with high accuracy.

## Installation
To install the necessary dependencies for this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/PP-OCRv4_OpenVINO.git
    cd PP-OCRv4_OpenVINO
    ```

2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Install OpenVINO:
    Follow the instructions on the [OpenVINO documentation](https://docs.openvino.ai/latest/openvino_docs_install_guides_installing_openvino.html) to install OpenVINO.

## Quick Start
To quickly start using the PP-OCRv4_OpenVINO project, follow these steps:

1. Download the PP-OCRv4 model and convert it to the OpenVINO format using the Model Optimizer.

2. Run the inference script:
    ```sh
    python infer.py --image_path path/to/your/image.jpg --model_path path/to/your/model.xml
    ```

3. The recognized text will be printed to the console.

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more details.

## Acknowledgment
This project is based on the PP-OCRv4 model developed by PaddlePaddle. We would like to thank the PaddlePaddle team for their contributions to the OCR community.
