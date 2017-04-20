# YT-8M_Challenge
Google Cloud &amp; YouTube-8M Video Understanding Challenge

Experience 1: jupyter notebook kernel install and remove

create an conda environment:<br>
conda create --name \<envName\> \<list of packages == version code\><br>

activate conda environment:<br>
source activate \<envName\><br>

install ipykernel:<br>
python\[3\] pip install ipykernel<br>

activate kernel and sepicify its name in jupyter notebook:<br>
python\[3\] -m ipykernel install --user --name \<myenv\> --display-name "Python (myenv)"<br>

remove kernel (when the env is activated):<br>
jupyter kernelspec list<br>
jupyter kernelspec remove \<the kernel name\><br>


Aaa