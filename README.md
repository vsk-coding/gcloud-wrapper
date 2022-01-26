# gcloud-wrapper!

Hi! This is a simple wrapper for gcloud cli with some limited predefined functions.
With this tool you can

 1. Create a cluster with predefined values
 2. List the clusters in  an active context
 3. Delete clusters in the active context
 4. Connect to available clusters in the context
 5. Activate a configuration
 6. List the current active configuration

# The how to's 

> Please note that this is a quick fix created to spin up a Kubernetes  cluster with minimal resources

 - Clone the repo 
		```
		 git cone git@github.com:vsk-coding/gcloud-wrapper.git
		 ```
	
 - Change directory to ***gcloud-wrapper***
		```
		 cd gcloud-wrapper
		 ``` 
 - Change permission of ***gcloud-wrapper***
		```
		 chmod +x gcloud-wrapper
		 ``` 
 - Copy ***gcloud-wrapper*** to ***/usr/local/bin*** with a name of your choosing
		```
		 sudo cp gcloud-wrapper /usr/local/bin/c
		 ``` 


Voila! You are all set. Let's use the script and create some clusters with ease.

> Please use ***sudo chmod +x /usr/local/bin/c*** if you get permission denied error while running the script after moving it to ***/usr/local/bin/c***

## Here is an asciinema

[![demo](https://github.com/vsk-coding/gcloud-wrapper/blob/main/gcloud-wrapper.gif)](gcloud-wrapper-ascii-cast-demo)
