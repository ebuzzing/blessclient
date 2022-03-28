# Changements:
Change lambda invoke to meet the new AWS IAM policy recurements. With the new configuration, blessclient invokes 
lambda finction as the following: arn:aws:lambda:......:stage (qualified ARN).
