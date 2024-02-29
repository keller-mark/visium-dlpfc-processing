# visium-dlpfc

Sample 151673

Data obtained from:
- RData file: https://www.dropbox.com/s/f4wcvtdq428y73p/Human_DLPFC_Visium_processedData_sce_scran_spatialLIBD.Rdata?dl=1 (linked from https://github.com/LieberInstitute/spatialLIBD/blob/ff49a2eaa1eb5477c5df8e46cf1652cdd8ec7244/R/fetch_data.R#L142C18-L142C125)
- Manual layer annotations: https://drive.google.com/drive/folders/10lhz5VY7YfvHrtV40MwaqLmWz56U9eBP?usp=sharing (linked from https://stagate.readthedocs.io/en/latest/T1_DLPFC.html)
- TIFF image: https://spatial-dlpfc.s3.us-east-2.amazonaws.com/images/151673_full_image.tif (linked from https://github.com/LieberInstitute/spatialLIBD/blob/ff49a2eaa1eb5477c5df8e46cf1652cdd8ec7244/README.md?plain=1#L235)

Data conversion

## RData to rds

```R
load("Human_DLPFC_Visium_processedData_sce_scran_spatialLIBD.Rdata")
saveRDS(sce, file="Human_DLPFC_Visium_processedData_sce_scran_spatialLIBD.rds")
```

## rds to AnnData with manual layer annotations

See Jupyter notebook

## All to SpatialData

TODO

## TIFF to OME-TIFF?

TODO

