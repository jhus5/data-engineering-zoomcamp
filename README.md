# data-engineering-zoomcamp

## Initial setup

### GCP

1. Sign up to GCP via: [GCP](https://cloud.google.com/free/). You can use your existing Google account to do so. 
2. Before proceeding, setup [authentication](https://cloud.google.com/compute/docs/authentication), if not already done so. Otherwise, you will be prompted to do so after you enable the Google Compute Engine.
- For this we used the Google Cloud CLI on Ubuntu. We chose to install the Google CLI via the snap package with the following command: 
	```
	snap install google-cloud-cli --classic
	```
- 	Then initialise by running:
	```
	gcloud init
	``` 
-	You will then be taken through the configuration of gcloud. Login when asked by selecting 'Y', a browser window should open with the Google login screen. Login with your google account that you used to sign up to GCP.
	You should then see:
	![Screenshot of a login success.](/images/setup/gcp2c.png)
3. 