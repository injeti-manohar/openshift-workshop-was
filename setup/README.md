# Workshop Lab Setup

This section contains instructions to access Openshift Clusters for those workshops that use IBM public cloud

## Create a free IBM Cloud Account ID

If you don't already have an IBM Cloud Account ID, point your browser to https://cloud.ibm.com and select `Create an IBM Cloud account`. You may use any email, including personal email, to apply. No credit card needed.

## Cluster assignment

- You will be given a URL specific to your workshpop, and a key. Point your browser 
to the URL. 
Enter the key for your workshop and your IBM ID to get assigned a cluster.
![Workshop assignment](images/Initial.jpg)
- Login to IBM cloud
- Ensure that the account selected is `2044184 - CP4AWorkshops`
![CP4Apps Account](images/CP4AppsAccount.jpg)
- Navigate to IBM CLoud > Resource list
![Resource list](images/ResourceList.jpg)
- Expand `clusters` and click on your cluster
![clusters](images/Clusters.jpg)
- For Openshift console, click `Openshift Web Console`
- For the cloud shell, click the `cloud shell` button.
![console](images/Console.jpg)

## Access the web terminal

1. On the OpenShift web console -> Networking -> Routes -> Select Project `lab` and click on the URL of route `tools` under Location.  The IBM Cloud login user is redirected to OAuth proxy for authentication and authorization and then redirected back to the route's URL with terminal displayed.

- Click on the route `tools` URL
![Route URL](images/tools_route.jpg)

- Click on `Log in with OpenShift`
![Oauth Proxy Authentication](images/oauthproxy.jpg)

- Click on `Allow selected permissions`
![Authorization](images/auth_permission.jpg)

- Note: The authorization permission page above may not display again in the later access when the information is already in the browser cookie cache.

- The web terminal is displayed, where you can access the resources on the IBM Cloud OpenShift cluster via CLI such as docker, oc, etc.

![Web Terminal](images/terminal.jpg)