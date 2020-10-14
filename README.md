# tp-devops1
Définir comment déployer, dans Kubernetes, une instance d’un projet à chaque fois qu’une pull-request 
est envoyée + mettre en place l’automatisation qui le fait.

## Pre-requis pour Centos 7
```
sudo yum -y update   # update all packages 
sudo yum -y install git wget   # install git and wget 
sudo yum -y install epel-release  # added extra packages
sudo yum -y install htop iotop iftop  # added monitoring tools
//Fork  
//     https://github.com/crunchy-devops/tp-devops1.git
and git clone your personnal repository of tp-devops1
git clone https://github.com/<your-repo>/tp-devops1.git
cd tp-devops1