# SSkin Model Uploader

Intended for uploading model to SSkin's GCP environment.

## What it does

- Load trained model from kaggle
- Add base64 preprocessing layer for receiving input in base64 string format
- Upload it to your Google Cloud Storage

## Requirement

Before using this, the following requirements should satisfy:

- A kaggle.json, authorized to access the corresponding kaggle output URL. Must be placed on default directory of Google Colabs.
- A GCP service account's service key (.json), authorized to upload object to a corresponding project's bucket.

## Steps to replicate

- Fork this repository
- Open the forked repository in google colabs
- Prepare kaggle.json and GCP SA key and place them accordingly
- Change the variables in source code to ur needs (like project name, bucket, and path)
- Run the whole thing


## LICENSE
See [LICENSE](https://github.com/Capstone-2022-C22-PS080/Model-Uploader/blob/main/LICENSE)
