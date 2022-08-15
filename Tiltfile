# docker build -t companyname/frontend ./frontend
allow_k8s_contexts('prodcls')
docker_build("idiotoflinux/dashoravm", ".")
k8s_yaml('k8s/app.yaml')
k8s_resource('dashoravmdevel', port_forwards=5005)
