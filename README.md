# Nextcloud on Docker with Face Recognition

This Dockerfile extends the nextcloud:apache Docker image with Face Regcognition Capabilities in your nextcloud images. Additionally this Dockerfile add cron via supervisory. 

After installation please install the Nextcloud App from https://apps.nextcloud.com/apps/facerecognition. Please activate the app after the installation. The Cronjob will soon start and will try to detect all faces within your pictures.

