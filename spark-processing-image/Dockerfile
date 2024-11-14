FROM 571004829621.dkr.ecr.eu-west-1.amazonaws.com/sagemaker-spark-processing:3.0-cpu

# Configure the kernel
RUN pip3 install ipykernel
RUN python3 -m ipykernel install --sys-prefix

# Make the default shell bash (vs "sh") for a better Jupyter terminal UX
ENV SHELL=/bin/bash
