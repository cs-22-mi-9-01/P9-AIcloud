# P9-AIcloud
Just for the AI-cloud

Run this command for setup
srun singularity build --fakeroot tensorflow_keras.sif Singularity

if out of memory run instead
srun --mem 64G singularity build --fakeroot tensorflow_keras.sif Singularity
