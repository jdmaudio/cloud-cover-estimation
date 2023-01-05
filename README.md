# cloud-cover-estimation

Juypter script which presents a method for cloud cover estimation (see CloudCover.ipynb). MultipleThreshold presents an alternative aproach

Daytime method uses a simple pixel red-blue ratio approach. The daytime implementation needs some improvement - the very bright areas around the sun are sometimes identified as clouds leading to cloud cover overestimation. Ideally a solar would be applied.

Two methods for night cloud estimation are also included (for night skies with moon and without). Both are inspired by papers listed in the script.
