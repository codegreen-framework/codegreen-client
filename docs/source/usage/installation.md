# Getting started

(setup)=
## Set up
### Sign up and generate an API key for your project

First, you need to set up an account and generate an API key to use the carbon-aware-API.

You can do this on our website at: 
Simply sign up with your email address, create a password and then click on the 'Request API Key' button
in the navigation bar. This will lead you to different page, where you can enter a name for your project
and click submit. And that's it.

### Why is an API required?
If you only want to use the prediction endpoint, this is of little interest to you. We just require
you to do it to avoid being spammed. However, beyond prediction, we offer more functionalities 
that help you shift your software stack to a more eco-friendly mode, by monitoring different projects.
You can submit usage reports to the database. This helps us to collect some data on eco-friendly computing,
something that is not yet done on a broader scale. Furthermore, it can help you to gain insight in your
operations. In fact you can generate more thant one API key and monitor the carbon footprint of your application by scope. 

## Installation

Now, that you have your API key, you can download and install the carbon-aware-API client package. We 
recommend using a virtual environment such as conda and installing the package from pip or conda.

```
conda create -n carbon-aware-ai 
conda install greenerai-client
```

And that's it! Head over to the next section <project:./quickstart.md> to find out how to make your code carbon-aware in one line!


:A reference from outside: 