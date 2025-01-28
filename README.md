# Populate Vectors Pipeline

This repo compiled a pipeline.yaml that populates vectors from 3 different sources by the user choice:
* S3 Bucket
* Code Repository
* List of URLs

Currently, the repository only supports processing PDFs. However, it can be extended to handle other data types as needed.


### Upload the pipeline as a job
If you want to upload the complied pipeline using a job this can be done using this repo: [ml-pipeline-importer-runner](https://github.com/RHEcosystemAppEng/ml-pipeline-importer-runner)

### How to execute
`pip install -r requirements.txt`
`python3 ./main.py`
