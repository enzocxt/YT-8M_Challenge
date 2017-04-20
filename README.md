# YT-8M_Challenge
Google Cloud &amp; YouTube-8M Video Understanding Challenge

Experience 1: jupyter notebook kernel install and remove

create an conda environment:
conda create --name \<envName\> \<list of packages == version code\>

activate conda environment:
source activate \<envName\>

install ipykernel:
python\[3\] pip install ipykernel

activate kernel and sepicify its name in jupyter notebook:
python\[3\] -m ipykernel install --user --name \<myenv\> --display-name "Python (myenv)"

remove kernel (when the env is activated):
jupyter kernelspec list
jupyter kernelspec remove \<the kernel name\>