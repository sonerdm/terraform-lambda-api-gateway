### Terraform AWS Lambda Example with API Gateway <img src="https://camo.githubusercontent.com/d13e208052a3e9d83243cd804635e60e4a238c43a86ce1bc6aea249c39c67709/68747470733a2f2f7777772e766563746f726c6f676f2e7a6f6e652f6c6f676f732f7465727261666f726d696f2f7465727261666f726d696f2d617232312e737667" alt="terraform" width="100" height="40"/>  <img src="https://github.com/github/explore/raw/main/topics/aws/aws.png" alt="aws" width="50" height="50"/>
</p>

Just enter the following commands sequentially if you already have an AWS account and did your configure
- make build
- make init
- make plan (Just to see the output)
- make apply

You can test it via postman or your terminal. After all things are done don't forget to enter the following command to destroy all resources.

```
curl "$(terraform output -raw base_url)/hello?name=MyName"
```

- make destroy
