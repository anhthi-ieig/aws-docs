# Amazon EC2 Instance Store

- Instance Store provides `temporary block-level storage` for your EC2 instance. Therefore, data will be lost if EC2 instance failure or is terminated

- This storage is `located on physically disks that are attached to the host computer` and `cannot be used for file sharing` between EC2 instances

- Instance store is `ideal for the temporary storage of information that changes frequently`, such as
  . Buffers
  . Caches
  . Scratch data
  . Other temporary content
