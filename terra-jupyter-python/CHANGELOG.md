## 0.0.5 - 11/26/2019

- Fix `WORKSPACE_BUCKET` environment variable

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.5

## 0.0.4 - 11/16/2019

- Update `terra-jupyter-base` version to `0.0.5`
- Removed apt-get upgrade for security purposes
`Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.4`

## 0.0.3 - 10/18/2019

- Update `terra-jupyter-base` version to `0.0.4`
`Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.3`

## 0.0.2 - 10/10/2019

Use jupyter base image 0.0.3

## 0.0.1 - 08/28/2019

- added pandas-gqb
- removed jupyter, jupyter-lab, unzip as they are in they base image
- removed google-cloud-core, was already satisfied as a dependency from other packages

| Package | Former Version | Current Version |
|---|---|---|
| google-api-core | 1.5.0 | 1.6.0 |
| keras | 2.2.0 | 2.1.6 |
| markdown | 2.6.9 | 2.4.1 |
| pysam | 0.13 | 0.15.1 |
| scipy | 1.0.0 | 1.2 |
| tensorflow | 1.9.0 | 2.0.0a0 |
| certifi |	2016.2.28 | 2017.4.17 |
| google-cloud-bigquery | 1.7.0 | 1.9.0 |

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.1
