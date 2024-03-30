# Using NVIDIA NeMo Guardrails with Amazon Bedrock

The following are the required steps to run this code on MacOS or Linux:

## Setup AWS credentials
*Skip this step if you plan to run this code within an AWS account* 
Follow [this guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html) to setup your local AWS profile.

## Configure your local environment
Install Python 3.12.

Create a Python virtualenv:
```
$ python3.12 -m venv .bedrock-nemo-env
```

Activate your virtualenv:
```
$ source .bedrock-nemo-env/bin/activate
```

Install the required dependencies:
```
$ pip3.12 install -r requirements.txt
```

Exit virtualenv:
```
$ deactivate
```

Enjoy!