# Alfresco on K8s workshop

In this workshop we will set up Alfresco on Kubernetes. This is not a Kubernetes installation workshop. In this workshop there are 3 options for using Kubernetes:

- Scaleway VM with kind
- Scaleway Kapsule
- Freestyle: choose your own K8s and make it work (advanced)

## Scaleway VM with kind

We can provision you with an Ubuntu VM. There is an installation script in the ubuntu-install folder, install.sh,  that installs:

- kind with ingress controller
- kubectl
- k9s
- helm

If you have Visual Studio Code, you can easily work over SSH.

## Excercises

1. Set up a basic Alfresco

In the helm folder, we prepared a helm chart with some basic configuration. Take a look at the configuration and change it where needed to make it work for you.

If you need a DNS to point to your server, we can help you with that. When everything is up and running. Alfresco should be reachable via a browser.

2. Enable Alfresco Digital Workspace

3. Enable Transformations