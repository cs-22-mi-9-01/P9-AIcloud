# P9-AIcloud
Just for the AI-cloud

First log in with this
ssh -l <aau email> ai-fe02.srv.aau.dk
  
then you have to bulid your singularity container. 

Outdated
(Run this command for setup
srun singularity build --fakeroot tensorflow_keras.sif Singularity

if out of memory run instead
srun --mem 64G singularity build --fakeroot tensorflow_keras.sif Singularity)


tutorials:

AAUs own tutorial:
https://aicloud-docs.claaudia.aau.dk/introduction/

This one is quite in depth: 
https://git.its.aau.dk/CLAAUDIA/docs_aicloud/src/branch/master/aicloud_slurm#user-content-slurm-basics
