# awsctx

A tool for switching `AWS_PROFILE`

![demo](https://github.com/RossyWhite/awsctx/blob/master/img/awsctx-demo.gif)

## Installation

Before install [yawsso](https://github.com/victorskl/yawsso) to sync CLI V1 profiles from CLI V2 (https://github.com/terraform-providers/terraform-provider-aws/issues/10851)

Put awsctx.sh script in some dir (/usr/local/bin), then

```bash
$ . /path/to/awsctx.sh
```

### To setup in your profile 

Add into your profile:

```
# AWSCTX
source "/usr/local/bin/awsctx.sh"
```
