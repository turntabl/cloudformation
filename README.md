# cloudformation

## Deploy command
```
aws cloudformation create-stack --stack-name <service-name> --template-body file://\$PWD/ecs-service.yml --parameters file://\$PWD/service-input.json
```

## Upload task-definition to s3
```
aws s3 cp service-task-definition.json s3://ecstasks
```
