# Poolsuite Diffusion for Replicate API

Model: [Funko Diffusion](https://huggingface.co/prompthero/funko-diffusion) 

Author: [@prompthero](prompthero.com)


### Download the weights:
```
$ mkdir weights
$ cd weights
$ git lfs install
$ git clone https://huggingface.co/prompthero/funko-diffusion
```
### Change the model name in predict.py

### Create a Docker image
```
docker build -t funko
```

### Create a model in Replicate

### Publish your model
````
$ cog login
$ cog push r8.im/prompthero/funko-diffusion
````

