# Singularity configuration for kraken2 container

A [Singularity](https://sylabs.io/docs/) definition for kraken2 workflow. 
The container is available at [https://singularity-hub.org/collections/](https://singularity-hub.org/collections/).

If [Singularity](https://sylabs.io/docs/) is installed locally, the container can be build locally (needs root access):

```bash
sudo singularity build kraken2.sif Singularity.202002 > build.log 2>&1
```

The container can also be downloaded from [Singularity Hub](https://www.singularity-hub.org/) without root access to the local machine like this:

```bash
singularity pull --name "kraken2.sif" sschmeier/container-kraken2
```

