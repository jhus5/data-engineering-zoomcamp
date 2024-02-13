# data-engineering-zoomcamp

## Initial setup

### GCP

1. Sign up to GCP via: [GCP](https://cloud.google.com/free/). You can use your existing Google account to do so. 
2. Before proceeding, setup [authentication](https://cloud.google.com/compute/docs/authentication), if not already done so. Otherwise, you will be prompted to do so after you enable the Google Compute Engine.
- For this we used the Google Cloud CLI on Ubuntu. We chose to [install the the snap package](https://cloud.google.com/sdk/docs/downloads-snap) with the following command: 
	```
	snap install google-cloud-cli --classic
	```
- 	Then [initialise gcloud](https://cloud.google.com/sdk/docs/initializing) CLI by running:
	```
	gcloud auth login
	``` 
- Provide the google account, password and allow permissions. If you were already logged in you can select your account and continue (as pictured).
	![Screenshot of a login.](/images/setup/gcp2b.png)
- click 'continue'
![Screenshot of a login.](/images/setup/gcp2bii.png)
- On the next screen click 'Allow' to provide Google SDK access to your account
![Screenshot of a login.](/images/setup/gcp2biii.png)
- If all goes well, we will be taken to the confirmation window:
![Screenshot of a login success.](/images/setup/gcp2c.png)

From here we wouls suggest that you look at some of the tutorials, in this case we'd suggest ['Compute Engine quickstart'](https://cloud.google.com/compute/docs/quickstart), where you can refer to guides. 
	
3. You can now proceed to [create SSH keys](https://cloud.google.com/compute/docs/connect/create-ssh-keys#gcloud).
- 
```

```
- 