# ec2asg-gitlab

Launches a GitLab AMI into an ASG of 1. Also provisions an IAM role for permissions and S3 bucket for backups.

## Usage

`ansible-playbook playbook.yml -i env/dev/hosts`

## TODO

* Have the instance auto-mount an EBS or EFS volume to provide the Docker host volume storage.
* Once auto-mounting storage, try running it on the spot market.
