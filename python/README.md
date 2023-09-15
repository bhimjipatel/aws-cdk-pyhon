# AWS CDK PYTHON
## Running Examples

### To run example
1. Ensure CDK is installed
```
$ npm install -g aws-cdk
```

2. Create a Python virtual environment
```
$ python3 -m venv .venv
```

3. Activate virtual environment

_On MacOS or Linux_
```
$ source .venv/bin/activate
```

_On Windows_
```
% .venv\Scripts\activate.bat
```

4. Install the required dependencies.

```
$ pip install -r requirements.txt
```

5. Synthesize (`cdk synth`) or deploy (`cdk deploy`) the example

```
$ cdk deploy
```

### To dispose of the stack afterwards:

```
$ cdk destroy
```

### Official Resources
- [Developer Guide](https://docs.aws.amazon.com/cdk/latest/guide/home.html)
- [API Reference](https://docs.aws.amazon.com/cdk/api/latest/docs/aws-construct-library.html)
- [CDK Workshop](https://cdkworkshop.com/)

### Unofficial/Community Resources
- [AwesomeCDK](https://github.com/kolomied/awesome-cdk)

## Additional Examples <a name="AddEx"></a>

| Example | Description |
|---------|-------------|
| [aws-cdk-changelogs-demo](https://github.com/aws-samples/aws-cdk-changelogs-demo) | A full serverless Node.js application stack deployed using CDK. It uses AWS Lambda, AWS Fargate, DynamoDB, Elasticache, S3, and CloudFront. | AWS |
