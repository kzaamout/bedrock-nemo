# Using NVIDIA NeMo Guardrails with Amazon Bedrock

The following are the required steps to run this code on MacOS or Linux:

## Setup AWS credentials
*Skip this step if you plan to run this code within an AWS account*

Follow [this guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html) to set up your local AWS profile.

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
## Run the code
Replace the *<YOUR_AWS_PROFILE_NAME>* placeholders in **config.yml** and **bedrock-nemo-test.py** files with your AWS profile name.

Execute the following code from the main directory:
```
python3.12 bedrock-nemo-test.py
```
- should not request information regarding hacking, brining down or shutting down websites
## 

Exit virtualenv:
```
$ deactivate
```

Enjoy!