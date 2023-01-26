Implementation on linux environment or servers, like Google Cloud Platform \
- using Anaconda list the environment \
`$ conda env list`
such as facewise-project

- python
current version python 3.9

- create/activate the new environment to use it \
`conda activate facewise-project`

- install required packages \
`$ pip install -r requirements.txt`

- To execute Facewise Low MAST ver `templates/facewise/facewise-low-mast.html`, add /facewisenewlm \
ex) http://analog-height-296717.uc.r.appspot.com/facewisenewlm

- To execute Facewise High MAST ver `templates/facewise/facewise-new.html`, add /facewisenew \
ex) http://analog-height-296717.uc.r.appspot.com/facewisenew

- To change the data location, change the key of `datastore.Entity` \
/main.py Line 72

- Install CORS (More information [here](https://www.youtube.com/watch?v=KruSUqLdxQA))
