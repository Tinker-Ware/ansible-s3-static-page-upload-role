# S3
Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. Amazon S3 provides easy-to-use management features so you can organize your data and configure finely-tuned access controls to meet your specific business, organizational, and compliance requirements. Amazon S3 is designed for 99.999999999% (11 9's) of durability, and stores data for millions of applications for companies all around the world.

# Role Variables
These variables are set by default to work with our Homepage repository on the branch currently mantaining the project code.
- `repo`: repository from which the code will be taken from.
- `branch`: repository's branch where the code is located.
- `bucket_name`: name of the bucket to which the static files will be uploaded.
- `aws_region`: region where the bucket is located.