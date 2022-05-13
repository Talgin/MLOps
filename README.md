## Face API in FastAPI
The implementation of our detection and recognition service using FastAPI, tritonclient.

### Installation
> pipenv shell
> pip install -r requirements
- Create folders: data (place datasets into this folder)

### Running the docker
> docker run --gpus all -it --network=host -v /home/tengri/PROJECTS/MLOps:/scripts --name mlops_container nvidia/cudagl:10.2-devel-ub18.04-conda /bin/bash 

### Issues

### TO-DO
- [ ] Git
- [ ] DVC
- [ ] Tracking results, meta
- [ ] Test on one-shot classification
- [ ] Test on different dataset
- [ ] Deployment test
