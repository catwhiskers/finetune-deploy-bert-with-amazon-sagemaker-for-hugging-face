
# Finetuning Hugging Face Bert with Chinese news datasets.
## This fork aims on demonstrating how to use Hugging Face to perform chinese document classification 
### The model used is bert-base-chinese. developed by [CKIP Lab](https://ckip.iis.sinica.edu.tw/). [Here](https://github.com/ckiplab/ckip-transformers) is the github link 
### Usage Instruction 
* Open a SageMaker Notebook in SageMaker Studio or Instance on Demand 
* Open terminal 
* `cd ~/SageMaker`
* `git clone https://github.com/catwhiskers/finetune-deploy-bert-with-amazon-sagemaker-for-hugging-face.git`
* Execute [this notebook](https://github.com/catwhiskers/finetune-deploy-bert-with-amazon-sagemaker-for-hugging-face/blob/main/finetune-bert-chinese.ipynb) 
  it will do data fetching, data processing, training job submission and setting up a endpoint for inference


## Security
See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License
This library is licensed under the MIT-0 License. See the LICENSE file.
