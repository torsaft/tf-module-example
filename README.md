# TF module example 

# Usage 


module "my_ec2_instance" {
  source = "github.com/torsaft/tf-module-example"

  ec2_instance_type      = "t3.micro"
  ec2_instance_name      = "My instance"
  number_of_ec2_instance = 1
  ec2_ami_id             = "you AMI ID to use to launch te instance"
}
~~~