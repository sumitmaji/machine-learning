# Setup Anaconda in Ubuntu

### Steps
1. Go to url https://www.anaconda.com/download/
2. Click on download button
3. Installation steps mentioned in https://docs.anaconda.com/anaconda/install/linux/
4. source ~/.bashrc
5. conda config --set auto_activate_base True
6. conda env create -f env.yaml
7. conda update -n base -c defaults conda
8. conda activate nlp_course
9. conda install -c conda-forge spacy
10. python -m spacy download en