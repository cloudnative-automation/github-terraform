# s3-terraform

说明：

`Provider Block`: provider 块配置了Terraform将会使用的AWS区域。你需要根据自己的需求更改region属性。

`Resource Block`: resource 块定义了一个资源，这里是aws_s3_bucket。my_bucket是Terraform中这个资源的名称，你可以根据需要更改这个名称。

`bucket`: 这里指定了S3 bucket的名称。这个名称需要在全AWS环境中唯一。

`acl`: 设置了bucket的访问控制列表，这里设置为private，意味着bucket内容只有拥有者可以访问。其他选项包括public-read、public-read-write等。

`Tags`: 为创建的S3 bucket添加了标签，这有助于资源管理和成本追踪。

