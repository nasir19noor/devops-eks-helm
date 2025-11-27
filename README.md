# devops-eks-helm

## Part 1: Configure AWS IAM Identity Provider
###Step 1: Create the OIDC Identity Provider in AWS

1. Log into AWS Console and navigate to IAM
2. Go to "Identity providers" in the left sidebar
3. Click "Add provider"
4. Select "OpenID Connect"
5. Enter the following details:
    - Provider URL: https://token.actions.githubusercontent.com
    - Audience: sts.amazonaws.com
6. lick "Get thumbprint" (AWS will automatically fetch it)
7. Click "Add provider"