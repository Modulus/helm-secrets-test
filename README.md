# Step 1
gpg --import privKey.asc


# Step 2
minikube start

# Step 3
1. helmfile diff
2. helmfile apply

# Step 4 
minikube service list

find jenkins and open it in your beerrrowserrrrr

# Additional
1. helm secreds dec secrets.yaml to decrypt secrets
2. yaml.dec are ignored in git, there are also commithooks to prevent acccidental commits of these.