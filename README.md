Test data to be used for automated testing with the Bioinformatics-Munich pipelines

> ⚠️ **Do not merge your test data to `master`! Each pipeline has a dedicated branch**

## Introduction

This repository contains various files for CI and unit testing of Bioinformatics-Munich pipelines and infrastructure and is built based on principles and contents from [nf-core](https://github.com/nf-core/test-datasets).

The principle for test data is as small as possible, as large as necessary.

## Documentation

Bioinformatics-Munich/test-datasets comes with documentation in the `docs/` directory, based on the one from [nf-core](https://github.com/nf-core/test-datasets/tree/master/docs):

01. [Use an existing test dataset](https://github.com/Bioinformatics-Munich/test-datasets/blob/master/docs/USE_EXISTING_DATA.md)

## Downloading test data

Due the potentially large number of large files in this repository for each pipeline, we highly recommend cloning only the branches you would use.

```bash
git clone <url> --single-branch --branch <pipeline/modules/branch_name>
```

To subsequently clone other branches[^1]

```bash
git remote set-branches --add origin [remote-branch]
git fetch
```

## Support

For further information or help, don't hesitate to get in touch with us.

[^1]: From [stackoverflow](https://stackoverflow.com/a/60846265/11502856)
