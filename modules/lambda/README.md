# AWS API PDF Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
pdf creation on AWS.

## Usage

```hcl
module "lambda-api-pdf" {
  source = "genstackio/layer-api-pdf/aws//modules/lambda"

  name   = "my-lambda-api-pdf"
}
```
