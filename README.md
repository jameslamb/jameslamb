### oh hey! 👋

I'm James, a data scientist / engineer from Chicago. My time on GitHub is mostly spent writing Python, R, and disgusting shell scripts on projects for data scientists and data engineers. My time off GitHub is spent at hip hop shows and watching reality TV.

<p align="center">
  <img src="https://media.giphy.com/media/26DMYwkCwa8G8xGcU/giphy.gif">
</p>

#### :shipit: open source stuff I'm maintaining

* [doppel-cli](https://github.com/jameslamb/doppel-cli): a command-line tool for checking if an R and Python library have the same interface
* [LightGBM](https://github.com/microsoft/LightGBM): a lightweight gradient boosting machine
* [pkgnet](https://github.com/uptake/pkgnet): R package for analyzing an R package's dependencies
* [prefect-saturn](https://github.com/saturncloud/prefect-saturn): Python client for runing [Prefect](https://github.com/PrefectHQ/prefect) flows on a Saturn Cloud Dask cluster
* [uptasticsearch](https://github.com/uptake/uptasticsearch): an R data frame client for Elasticsearch

#### ✋ open source stuff I've been making little contributions on

* [prefect](https://github.com/PrefectHQ/prefect): a workflow management thing in Python that plays nicely with Dask
* [xgboost](https://github.com/dmlc/xgboost): another gradient boosting machine

### 😊 open source contributions I'm proud of

<details><summary>click for details</summary>

The pull requests below were chosen to showcase the types of software work I've done. This list is not exhaustive.

#### Features

* adding `Webhook` storage to `prefect`: https://github.com/PrefectHQ/prefect/pull/3000
* adding `autoconf`-based builds of LightGBM's R package: https://github.com/microsoft/LightGBM/pull/3188
* making `snowflake-connector-python` compatible with `pyjwt` 1.x and 2.x: https://github.com/snowflakedb/snowflake-connector-python/pull/604
* allow tight control over ports in LightGBM distributed traiining with Dask: https://github.com/microsoft/LightGBM/pull/3994
* cut compiled size of `{lightgbm}` by ignored CLI-only objects: https://github.com/microsoft/LightGBM/pull/3566
* allow use of multiple image pull secrets in `prefect` kubernetes agent: https://github.com/PrefectHQ/prefect/pull/3596
* replace single-shot HTTP requests with `httr::RETRY()` in various R packages
    - project I led at Chi R Collab 2020: https://github.com/chircollab/chircollab20/issues/1
    - `{sergeant}` (one example): https://github.com/hrbrmstr/sergeant/pull/42

#### Docs

* tutorial on distributed LightGBM training with Dask: https://github.com/microsoft/LightGBM/pull/4030
* early stopping example in XGBoost Dask docs: https://github.com/dmlc/xgboost/pull/6501
* detailed information on how LightGBM parameters affect training speed: https://github.com/microsoft/LightGBM/pull/3628
* guide on how to find valid memory and CPU combinations for ECS / Fargate clusters in `dask-cloudprovider`: https://github.com/dask/dask-cloudprovider/pull/156

#### Bug Fixes

* make multioutput behavior of `dask-ml` regression metrics consistent with `scikit-learn`: https://github.com/dask/dask-ml/pull/820
* fix saving Dask Random Forest models in `cuml`: https://github.com/rapidsai/cuml/pull/3388
* fix checks for availability of `mm_malloc` in `{lightgbm}` autoconf-based builds: https://github.com/microsoft/LightGBM/pull/3510
* fix broken plots in `{lightgbm}`'s docs site: https://github.com/microsoft/LightGBM/pull/3508
* factor out dependency on `gendef.exe` for compiling XGBoost and LightGBM R packages with Visual Studio compilers and R 4.0:
    - `{xgboost}`: https://github.com/dmlc/xgboost/pull/5764
    - `{lightgbm}`: https://github.com/microsoft/LightGBM/pull/3065

#### Infrastructure / CI

* automatically publish `prefect-saturn` to PyPI when a new release is created: https://github.com/saturncloud/prefect-saturn/pull/7
* moving LightGBM CI jobs from Travis to GitHub Actions:
    - https://github.com/microsoft/LightGBM/pull/3745
    - https://github.com/microsoft/LightGBM/pull/3726
    - https://github.com/microsoft/LightGBM/pull/3119
* move `{uptasticsearch}` CI to GitHub Actions: https://github.com/uptake/uptasticsearch/pull/217
* add CI job testing `{lightgbm}` within ASAN and UBSAN sanitizers: https://github.com/microsoft/LightGBM/pull/3439
* reduce data loading work in LightGBM tests by caching data loading calls: https://github.com/microsoft/LightGBM/pull/3486
* add Dockerfile to build an image for testing the Apache Arrow R package: https://github.com/apache/arrow/pull/2770

</details>

#### 💰 things I do for money

* software engineer at [Saturn Cloud](https://www.saturncloud.io/), where we're building "Databricks for Dask"
* adjunct instructor at Marquette University, where I teach "Intro to R Programming"

#### :computer: conference talks

I've given talks on Dask, LightGBM, R, and other random stuff. For a full list and links to videos, see https://github.com/jameslamb/talks#gallery.

#### :microphone: talk to me!

My DMs are open if you want to talk about open source, data science careers, *Jersey Shore*, or anything else.

* :bird: Twitter: https://twitter.com/_jameslamb
* :link: LinkedIn: https://www.linkedin.com/in/jameslamb1/
