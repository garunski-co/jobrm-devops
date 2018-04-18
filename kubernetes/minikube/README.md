# jobrm
Keep track of job applications

# minikube 

`minikube start --vm-driver=hyperv --hyperv-virtual-switch=Minikube`

1. Powershell: `"minikube mount $($pwd.Path):/code" | Invoke-Expression`
1. CMD: `minikube mount %cd%:/code`
1. Bash: `minikube mount $(pwd):/code`

# jenkins

`helm install --name jenkins --values ./kubernetes/minikube/jenkins-helm.yaml stable/jenkins`
or
`helm upgrade jenkins --values ./kubernetes/minikube/jenkins-helm.yaml stable/jenkins --install`