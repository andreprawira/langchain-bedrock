# Use Langchain Framework with AWS Bedrock to chat your own data

To manually create a virtualenv on Windows:

```
python -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
.\.venv\Scripts\activate
```

Once the virtualenv is activated, you can install the required dependencies.

```
pip install -r requirements.txt
```

Configure AWS creds locally and ensure you have IAM access to use AWS Bedrock and that you have permission to use the FMs

```
aws configure 
```

Once dependencies are installed and venv is activated then execute the file

```
python .\bedrock-workshop.py
```