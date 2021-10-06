# I want to...

## Opinionated advices for recurring topics

There are a lot of awesome-* things, but what do __you__ actually use?


## ... pull data from multiple data sources and play around with them

Use [Spark](https://spark.apache.org)

## ... process data in a reproducible fashion without lossing track of spreadsheet cell dependencies

Use [Pandas](https://pandas.pydata.org)

## ... orchestrate a set of actions across several machines

Sorry. Though [google/zx](https://github.com/google/zx) and [Ansible](http://ansible.com) are kind of close enough.

## ... recreate my servers' configuration from ground up in case of failure/change of IaaS provider/OS update

Use [Ansible](http://ansible.com). Better yet, roll out [Kubernetes](https://kubernetes.io)

## ... throw together a script to perform some recurring task using a bunch of Unix tools I know well in understandable and supportable way

Sorry. Tough [google/zx](https://github.com/google/zx) and [Tcl](https://www.tcl.tk) feel promising

## ... create data visualizations fast

Use [Jupyter](https://jupyter.org) and [matplotlib](https://matplotlib.org)

## ... keep my applications running despite flaky machines

Use [Kubernetes](https://kubernetes.io)


## ... understand Artificial Intelligence/Machine Learning/Deep Learning/Data Science/Big Data

In short:
* DS = ways of working with data in general
* AI = ways of making machines intelligent
* DL = technique of training neural networks which are the epitome of connectionist approach to artificial intelligence; hyped due to greatly pushing the approach forward and sprawling wide spectrum of research around applicability of different network architectures towards specific problems
* ML = generally any techniques where a machine learns something, included into AI and DS, includes DL
* Big Data = tools and approaches on how to deal with large quantities of data (≈can't fit a single machine) on commodity hardware

## ... explore DL

Read 
* [Introduction to Machine Learning with Python](https://www.amazon.co.uk/dp/1449369413)
* [Python Machine Learning By Example](https://www.amazon.co.uk/dp/B01MT7ATL5)
* [Python for Data Analysis](https://www.amazon.co.uk/dp/1491957662)
* [The Elements of 
Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)
* [Deep Learning](https://www.deeplearningbook.org)

Play around with any one of [TensorFlow](https://www.tensorflow.org), [Keras](https://keras.io), [PyTorch](https://pytorch.org). [Hugging Face](https://huggingface.co), maybe?


## ... explore self-driving

Go through [Udacity's Arificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373)

## ... know which requests some pesky app is making

Use [mitmproxy](https://mitmproxy.org)

## ... stop wasting time figuring out how to run an application

Use [Docker](https://www.docker.com)

## ... stop wasting time figuring out how to build an application from the source code

Use [make](https://www.gnu.org/software/make/manual/html_node/index.html) and build inside Docker


## ... keep some private data

Use [VeraCrypt](https://github.com/veracrypt/VeraCrypt)

## ... write some automation without caring about deployment or making sure it will be reliably run

Use [repl.it](https://replit.com), maybe? Or [Heroku](https://www.heroku.com)? Or [AWS Lambda](https://aws.amazon.com/lambda/)? Keywords: no-code, low-code, serverless

## ... send notifications from your machine to your email

Use [postfix](http://www.postfix.org) with custom transport using [gmail-oauth2-tools](https://github.com/google/gmail-oauth2-tools/tree/master/go/sendgmail)

## ... shrink disk space used by duplicate virtual environments

Develop [inside Docker](https://code.visualstudio.com/docs/remote/containers). Produce images tailored for specific purposes (e.g. image for data science, image for django development, image for go development, etc)

## ... keep track of tasks to do

Use [org-mode](https://orgmode.org) & [beorg](https://beorgapp.com)

## ... develop a habit

Use [Nomie](https://nomie.app)

## ... manage PKI infrastructure

Use [Vault](https://www.vaultproject.io/docs/secrets/pki)
