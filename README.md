# reproducibility-tutorial
This is a tutorial for FOSS 2020 online on reproducibility 
    1  ls
    2  ls /
    3  cd /scratch/
    4  ls
    5  /opt/conda/bin/conda search -c bioconda snakemake
    6  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
    7  ln -s /opt/conda/bin/* /bin
    8  ln -s /opt/conda/lib/* /usr/lib
    9  snakemake --version
   10  clear
   11  sudo apt-get update
   12  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   13  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   14  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   15   $(lsb_release -cs) \
   16   stable"
   17  sudo apt-get update
   18  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   19  docker run hello-world
   20  history
   21  cd /scratch/reproducibility-tutorial/
   22  history >>README.md
   23  nano README.md
   24  nano README.md
   25  nano README.md
   26  nano README.md
   27  head README.md 
   28  ls
   29  cd /scratch
   30  df -h
   31  git clone https://github.com/lizsuter/reproducibility-tutorial.git
   32  ls
   33  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   34  ls
   35  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   36  ln -s /opt/conda/pkgs/*/bin/* /bin
   37  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   38  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   39  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   40  /opt/conda/bin/pip install bash_kernel
   41  /opt/conda/bin/pip install ipykernel
   42  /opt/conda/bin/python3 -m bash_kernel.install
   43  /opt/conda/bin/conda/ search -c bioconda bowtie
   44  /opt/conda/bin/conda/ search bowtie
   45  /opt/conda/bin/conda search bowtie
   46  /opt/conda/bin/conda search -c bioconda bowtie
   47  clear
   48  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   49  ls
   50  pwd
   51  ls /
   52  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   53  ls /scratch
   54  cd /scratch
   55  ls
   56  git clone https://github.com/lizsuter/reproducibility-tutorial.git
   57  ls
   58  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   59  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   60  bash Miniconda3-latest-Linux-x86_64.sh -b -p -u /opt/conda
   61  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   62  ln -s /opt/conda/pkgs/*/bin/* /bin
   63  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   64  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   65  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   66  /opt/conda/bin/pip install bash_kernel
   67  /opt/conda/bin/pip install ipykernel
   68  /opt/conda/bin/python3 -m bash_kernel.install
   69  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   70  /opt/conda/bin/conda search -c bioconda snakemake
   71  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   72  ln -s /opt/conda/bin/* /bin
   73  ln -s /opt/conda/lib/* /usr/lib
   74  snakemake --version
   75  sudo apt-get update
   76  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   77  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   78  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   79  sudo apt-get update
   80  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   81  docker run hello-world
   82  cd /scratch/reproducibility-tutorial/
   83  history >>README.md
