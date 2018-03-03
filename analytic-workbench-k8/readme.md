# Install Kubectl

https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-with-homebrew-on-macos
1. 
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/darwin/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
