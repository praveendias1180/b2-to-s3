# BB to S3 

WordPress plugin **Continuous Delivery** to AWS S3.

Zip the selected files and deliver the archive to a AWS S3 bucket on new **tag push** to Bitbucket private repository.
Also the installed plugins will be able to see the update and pull the updated WordPress plugin.

```
git push bb --tags
```

# BitBucket Pipelines

![B2 2 S3](b2-2-s3.gif)

# AWS S3

Delivered files from Bitbucket on tag push.

![S3 Delivery](s3-delivery.png)

