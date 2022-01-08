## Amazon EC2 Instance Store

- EC2 Instance Store is a `high-performance block-level storage` for your EC2 instance

- EC2 Instance Store is `located on physically disks` that are attached to the host computer. Therefore, `data will be lost if EC2 instance failure or is terminated`

- EC2 Instance Store `cannot be used for file sharing` between EC2 instances and `cannot be removed`

- Instance store is `ideal for the temporary storage of information that changes frequently`, such as

  - Buffers
  - Caches
  - Scratch data
  - Other temporary content
