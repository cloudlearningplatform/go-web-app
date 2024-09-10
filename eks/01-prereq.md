prerequisites


1. kubectl – A command line tool for working with Kubernetes clusters. For more information, see Installing or updating kubectl.

    curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"

    chmod +x ./kubectl

    sudo mv ./kubectl /usr/local/bin/kubectl


2. eksctl – A command line tool for working with EKS clusters that automates many individual tasks. For more information, see Installing or updating.

     curl --silent --location "https://github.com/weaveworks/eksctl/releases/download/$(curl --silent "https://api.github.com/repos/weaveworks/eksctl/releases/latest" | grep -Po '"tag_name": "\K[^"]*')/

     eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp

     sudo mv /tmp/eksctl /usr/local/bin


2. AWS CLI – A command line tool for working with AWS services, including Amazon EKS. For more information, see Installing, updating, and uninstalling the AWS CLI in the AWS Command Line Interface User Guide. After installing the AWS CLI, we recommend that you also configure it. For more information, see Quick configuration with aws configure in the AWS Command Line Interface User Guide.

  For Linux / macOS To install the latest version of AWS CLI on Linux or macOS, run the following command:
 
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

   unzip awscliv2.zip

   sudo ./aws/install
