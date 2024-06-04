# Patches

## AWS Transfer Server - IDP authentication using Secrets Manager Lambda

The [CF template we use that is recommended by AWS](https://s3.amazonaws.com/aws-transfer-resources/custom-idp-templates/aws-transfer-custom-idp-secrets-manager-apig.template.yml) hardcodes a particular Secrets Manager structure to adhere to but ours is different so we have created this patch.
