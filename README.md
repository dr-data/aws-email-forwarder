# AWS Email Forwarder

Inspired by [this article](https://aws.amazon.com/blogs/messaging-and-targeting/forward-incoming-email-to-an-external-destination/) from the AWS Blog and [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder).

What it does:  
Receive mail at `*@my-domain.com` and forward it to `me@mail-provider.com`.

## Install
Follow the instructions from the [AWS article](https://aws.amazon.com/blogs/messaging-and-targeting/forward-incoming-email-to-an-external-destination/) and replace their Lamba function code by the code found in [lambda_function.py](https://github.com/mlgx/aws-email-forwarder/blob/master/lambda_function.py).