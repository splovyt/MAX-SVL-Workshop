<img src="https://raw.githubusercontent.com/splovyt/MAX-SVL-Workshop/master/docs/ibm-logo.png" height=50 align="right">

# Getting Started with Deep Learning and the Model Asset Exchange (MAX)

This repository contains all information for the hands-on part of the session.

Slides URL: **[Add slides URL here]**

## Hands-On MAX Tutorial

<img src="https://raw.githubusercontent.com/splovyt/MAX-SVL-Workshop/master/docs/object-detection.png" width=300 align="right">

### 1. Install and run the MAX Object Detector

Getting started with the bleeding edge of Deep Learning is extremely easy.. and free!

In this part, we will demonstrate how you can use AI to detect objects in an image. The only prerequisite is having [Docker](https://docs.docker.com/install/) installed on your system. Please follow the installation instructions [here](https://docs.docker.com/install/).

Following the installation of docker, you can check whether the installation was successful by opening the terminal and copying the following:

`docker -v`

If the above command returns the Docker version, you are pretty much there! Getting the Object Detector to run is as easy as copying the command below into your terminal. This will take some time depending on your download speed.

`docker run -it -p 5000:5000 codait/max-object-detector`

If everything works well, you will see the following message as output:

```
 * Serving Flask app "MAX Object Detector" (lazy loading)
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
```

That works? Great! Go to `http://0.0.0.0:5000/` to check out the REST API, or to `http://0.0.0.0:5000/app` to try out the webapp. In step 2, we will discuss how to use the Object Detector.

If you would like a more detailed tutorial, or if you are having trouble, please check out
- [MAX Object Detector README](https://github.com/IBM/MAX-Object-Detector/blob/master/README.md)
- [Blogpost on Medium by Patrick](https://medium.com/ibm-watson-data-lab/ready-to-use-deep-learning-models-f234be9ccfc3)
- [Blogpost on Medium by Saishruthi](https://medium.com/ibm-watson-data-lab/learn-what-lies-beneath-our-ready-to-run-deep-learning-models-c6a3edc4cc1d)

### 2. Using the Object Detector

[How to use the object detector]

### 3. Explore other MAX Models

[See Notebook in this Repository]

### 4. (Bonus) Integrate a MAX Deep Learning Model in your own web application

Have you always wanted to launch your own AI-powered webservice? Using the following tutorial, you will be able to spin up and deploy your own webservice in a matter of minutes:

https://github.com/IBM/max-tutorial-app-python

In this tutorial, you will
- Download the backbone of a basic web application
- Integrate the Deep Learning MAX model of your choice in the webapp
- Launch the webapp!

### Done, but want to learn more?

Check out https://developer.ibm.com/exchanges/models/ or contact one of the hosts for further information.

- [Blogpost on Medium by Patrick](https://medium.com/ibm-watson-data-lab/ready-to-use-deep-learning-models-f234be9ccfc3)
- [Blogpost on Medium by Saishruthi](https://medium.com/ibm-watson-data-lab/learn-what-lies-beneath-our-ready-to-run-deep-learning-models-c6a3edc4cc1d)
