# Step 1
gpg --import privKey.asc


# Step 2
minikube start

# Step 3
helmfile diff
helmfile apply

# Step 4 
minikube service list

find jenkins and open it in your beerrrowserrrrr

# Additional
helm secreds dec secrets.yaml to decrypt secrets
yaml.dec are ignored in git, there are also commithooks to prevent acccidental commits of these.