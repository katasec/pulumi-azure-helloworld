# Overview

This is a standard `hello world` style Pulumi program for Azure straight from the Pulumi docs. This is a sample repo used to test Pulumi's Automation API from a [git remote ](https://github.com/pulumi/automation-api-examples/tree/main/go/git_repo_program)

# To run this:

- Clone repo
- Setup stack name. The format is `org name/stack name/env`
```
pulumi new azure-go -s katasec/pulumi-azure-helloworld/dev
```

- Deploy Pulumi Stack
``` 
pulumi up -f
```

- Destroy Pulumi Stack and remove it
```
pulumi destroy -f
pulumi stack rm katasec/dev -y
```

