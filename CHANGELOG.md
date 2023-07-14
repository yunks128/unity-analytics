# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

--------

# [Unity Release 23.2] - 2023-07-13

- unity-analytics : [https://github.com/unity-sds/unity-analytics/releases/tag/v0.2.0](https://github.com/unity-sds/unity-analytics/releases/tag/v0.2.0)
- unity-analytics-bcdp : [https://github.com/unity-sds/unity-analytics-bcdp/releases/tag/v0.2.0](https://github.com/unity-sds/unity-analytics-bcdp/releases/tag/v0.2.0)
- unity-analytics-dapa : [https://github.com/unity-sds/unity-analytics-dapa/releases/tag/v0.2.0](https://github.com/unity-sds/unity-analytics-dapa/releases/tag/v0.2.0)
- unity-analytics-sdap : [https://github.com/unity-sds/unity-analytics-sdap/releases/tag/v0.1.0](https://github.com/unity-sds/unity-analytics-sdap/releases/tag/v0.1.0)


## Epics:
- EPIC: `Time series transformations through a Unity DAPA endpoint`
    - [unity-analytics #38] Design interface mechanism between Unity DAPA and SDAP deployed in MCP/EKS
        - [https://github.com/unity-sds/unity-analytics-dapa/blob/devel/doc/openapi.yaml](https://github.com/unity-sds/unity-analytics-dapa/blob/devel/doc/openapi.yaml)
    - [unity-analytics #49] Develop the interface between Unity DAPA and SDAP deployed in MCP/EKS
        - [https://github.com/unity-sds/unity-analytics-dapa/tree/devel](https://github.com/unity-sds/unity-analytics-dapa/tree/devel)
    - [unity-analytics #58] Package Process Mapper as Docker Container
    - [unity-analytics #57] Set up mock integration for SDAP Time Series API in AWS API Gateway
        - Example: [https://55j2i6e704.execute-api.us-west-2.amazonaws.com/sdap-dev/timeSeriesSpark?ds=MUR25-JPL-L4-GLOB-v4.2\_analysed\_sst&minLon=-77.0&minLat=35.0&maxLon=-70.0&maxLat=42.0&startTime=2018-01-01T00:00:00Z&endTime=2018-12-31T00:00:00Z](https://55j2i6e704.execute-api.us-west-2.amazonaws.com/sdap-dev/timeSeriesSpark?ds=MUR25-JPL-L4-GLOB-v4.2_analysed_sst&minLon=-77.0&minLat=35.0&maxLon=-70.0&maxLat=42.0&startTime=2018-01-01T00:00:00Z&endTime=2018-12-31T00:00:00Z)
- EPIC: `Regrid Earth remote sensing data products`
    - [unity-analytics #55] Test BCDP application on laptop with `cwl-runner`
    - [unity-analytics #44] Use U-SPS APIs to deploy the BCDP OGC application to ADES-HySDS
    - [unity-analytics #63] Use U-SPS APIs to run the process step of BCDP OGC application on ADES-HySDS

--------

# [Unity Release 23.1] - 2023-04-07

- unity-analytics : [https://github.com/unity-sds/unity-analytics/releases/tag/v0.1.0](https://github.com/unity-sds/unity-analytics/releases/tag/v0.1.0)
- unity-analytics-bcdp : [https://github.com/unity-sds/unity-analytics-bcdp/releases/tag/v0.1.0](https://github.com/unity-sds/unity-analytics-bcdp/releases/tag/v0.1.0)
- unity-analytics-sdap : [https://github.com/unity-sds/unity-analytics-sdap/releases/tag/v0.1.0](https://github.com/unity-sds/unity-analytics-sdap/releases/tag/v0.1.0)


## Epics:
- EPIC: `Time series transformations through a Unity DAPA endpoint`
    - [unity-analytics #63] Prepare the dataset files for ingest into SDAP
        - [https://github.com/unity-sds/unity-analytics-sdap/tree/main/img\_to\_nc](https://github.com/unity-sds/unity-analytics-sdap/tree/main/img_to_nc)
- EPIC: `Regrid Earth remote sensing data products`
    - [unity-analytics #35] Develop new BCDP notebook with an extended set of Papermilled parameters
        - [https://github.com/unity-sds/unity-analytics-bcdp](https://github.com/unity-sds/unity-analytics-bcdp)
    - [unity-analytics #53] Modify BCDP papermilled notebook to set specific s3 URL as input parameter
        - [https://github.com/unity-sds/unity-analytics-bcdp](https://github.com/unity-sds/unity-analytics-bcdp)
    - [unity-analytics #36] Use U-ADS tools to build OGC application package for the extended BCDP notebook
        - [https://github.com/unity-sds/unity-analytics-bcdp/tree/main/cwl](https://github.com/unity-sds/unity-analytics-bcdp/tree/main/cwl)

--------
