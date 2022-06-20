# IAM Role
An elementary blueprint for defining an AWS Identity &amp; Access Management Role
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role

Not this is a basic version with a single auth rule

as in example

"action" : "sts:AssumeRole",
        "Effect" : "Allow",
        "Sid"    : "",
        
        Service" : "ec2.amazonaws.com"  (might be plural)