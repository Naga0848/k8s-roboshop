# Understanding the dependencies

    understand the dependcies between service, i.e., we should know which service depends on other service and accordingly we can figure out the env variables, i.e., configmaps

# And we should not forget to refer the services, configmaps etc, when we created them

# Main parts in Orchestration

    1. Build the image   ---> this is already done in Docker
    2. Configure the image ---> we are working on this in K8s

# First we need to create a namespace to deploy the roboshop on k8s

# For every service, we should create only deployment,  because replicaset and pod are the subset of deployments

# Also, remeber that we are maintaining all the k8s resourches in a single yaml file i.e., we write, deployment, service, configmaap and secrets in a single yaml file

