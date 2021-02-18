````shell
sail composer require aws/aws-sdk-php "~3.0"
````


````shell
sail artisan make:job ProcessPodcast
````

.env
````
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=eu-west-1
SQS_PREFIX=https://sqs.us-east-1.amazonaws.com/your-account-id
SQS_QUEUE=your-queue-name
````
