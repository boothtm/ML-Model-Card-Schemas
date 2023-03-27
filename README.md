# ML-Model-Card-Schemas

The purpose of model cards is to focus on purpose, performance, safety, security, transparency, responsible use [insert many citations here].
We extend these concepts to include inference costs to address the use on resource limited systems, and this is the initial iteration of defining a standard schema for a time-series Recurrent Neural Network (RNN) based ML model.  There needs to be many more schemas based on different categories of AI or ML models and they should utilize commonalities where possible.

I'm not going to pretend this will be the final solution, but I wanted to start this effort somewhere and make it available for everyone to improve on.
Additional motivation for this schema is reference in this paper [cite my SPIE paper].

These schemas can be created as YAML files or by adding these variables to the Neural Network class itself.  In this instance, I've included them in the LSTM.py class object I used to train the models.  To ensure these .pt model files will be read properly I am also including a Python conda environment configuration file.  This will spin up the Python tools used to create the model and will be able to read them as well.  A docker image could also be a convienent way to do this as well.
