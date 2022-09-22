# jetson_dev

This repo is an experimentation repo for development with the Jetson Xavier AGX kit. The examples used in the contained nb's are of PyTorch. The purpose of the repo is to test the various models and performances on the Jetson Xavier AGX device. 

- [x] FashionMNIST ANN Quickstart notebook
- [x] FashionMNIST ANN Quickstart notebook MAXV power mode

## remote host to jupyter notebook

SSH into Jetson Xavier 
<code>ssh <remote-user>@<remote-host><code>
Run jupyter lab from the desired folder
<code>jupyter-lab<code>
SSH into jupyter remote server 
<code> ssh -N -L localhost:<local-port>:localhost:<remote-port> <remote-user>@<remote-host><code>
Open <code>http://localhost:<local-port>/<code> in the browser
