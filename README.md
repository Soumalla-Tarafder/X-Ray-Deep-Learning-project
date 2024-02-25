# deeplearningproject

## This is a deep learning created maintain full moduler standard to check X-Ray reports.

## We store our data into s3 bucket

## How to Setup:

```bash
conda create -n x-ray python=3.8 -y
```

```bash
conda activate x-ray
```

```bash
pip install -r requirements.txt
```

-- downalod aws cli from this link and setup link :

```bash
 https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

```

--- set IAM

--- create user

```bash
aws configure

```

-- after successfully run the model_trainer pipeline code to check the bentoml model save or not is -- 

```bash

bentoml models list

```