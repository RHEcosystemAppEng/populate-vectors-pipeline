# RAG LLM Pipeline

This repo complied a pipeline.yaml that populate vectors from 3 diffrent sources by the user choice:
* S3 Bucket
* Code Repository
* List of URLs

Currently, the repository supports processing PDFs only. However, it can be extended to handle other data types as needed.


### Upload the pipeline as job
If you want to upload the complied pipeline using a job this can be done using this repo: **TODO**

### How to execute
`pip install -r requirements.txt`
`python3 ./main.py`