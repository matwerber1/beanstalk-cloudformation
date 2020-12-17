# beanstalk-cloudformation

My attempt to deploy a Beanstalk Java SE app from scratch via CloudFormation.

## Status

Not currently working, environment fails to deploy without any meaningful error message. It just says:

```
Environment failed to launch as it entered Terminated state
```

## Warning

For test purposes, the IAM Beanstalk Service role and EC2 Auto-scaling role I've defined have `AdministratorAccess` managed policy (so I can rule out permissions as the problem). This is of course not recommended for security reasons.
