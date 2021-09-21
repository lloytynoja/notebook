# notebook
Basic starter kit with virtualenv and jupyter notebook

## Python

Create a new virtual environment 

<pre>
python -m venv [name]
</pre>

Activate virtual environment

<pre>
# Linux
source [name]/bin/activate

# Windows 
.\[name]\Scripts\activate  
</pre>

Dependencies

<pre>
# Install dependencies
python -m pip install --upgrade pip

# Ipykernel (interactive shell for jupyter)
pip install ipykernel
python -m ipykernel install --user --name=[kernel_name]
</pre>
