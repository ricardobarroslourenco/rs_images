# RS Images

Repository based on Mambaforge image to create Apptainer containers for CPU-only nodes, aiming Remote Sensing workflows.

Released builds available at Docker Hub: https://hub.docker.com/repository/docker/ricardobarroslourenco/mambaforge_custom_geo_cpuonly/

# Change Log
Major updates here. For details, see the commit log.
## v0.2 
- Adds Cartopy offline bases (for HPC usage)
### v0.2.2
- Fix issue of creating a new conda env (instead, will be updating the base env)

### v0.2.3
- Fix issue 
- Adds Fiona (to allow clipping)

## v0.1 
- Initial release based in a mambaforge image plus some Xarray + Dask for CPU