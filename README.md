# anaconda
How to set up python environment?

# install anaconda on mac
https://www.anaconda.com/products/distribution#macos

# anaconda commands

list the environment of conda
conda env list

list all installed packages
conda list

Create new environment
conda create --name py39

Activate py39 environment
conda activate py39

Deactivate
conda deactivate

# install pandas packages
conda install pandas

# install scikit-learn packages
conda install scikit-learn

# install imbalanced-learn packages
conda install -c conda-forge imbalanced-learn

# install tensorflow packages
conda install -c conda-forge tensorflow

conda install -c conda-forge/label/broken tensorflow

conda install -c conda-forge/label/cf201901 tensorflow

conda install -c conda-forge/label/cf202003 tensorflow

# install matplotlib packages
https://anaconda.org/conda-forge/matplotlib

conda install -c conda-forge matplotlib

conda install -c conda-forge/label/testing matplotlib

#UnavailableInvalidChannel: HTTP 404 NOT FOUND for channel conda-forge/label/testing/gcc7 <https://conda.anaconda.org/conda-forge/label/testing/gcc7>
conda install -c conda-forge/label/testing/gcc7 matplotlib

conda install -c conda-forge/label/cf202003 matplotlib

conda install -c conda-forge/label/matplotlib_rc matplotlib

conda install -c conda-forge/label/gcc7 matplotlib

conda install -c conda-forge/label/broken matplotlib

conda install -c conda-forge/label/rc matplotlib

conda install -c ocnda-forge/label/cf201901 matplotlib

conda install -c conda-forge/label/broken-test matplotlib
