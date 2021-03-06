# Bengali Document Summarizer
Bengali single document summarizer demo


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development, testing purposes and as well as in production machine. See deployment for notes on how to deploy the project on a live system.


## Python Version
Minimum python version should have 3.x.x or upper

## Installing

A step by step series of examples that tell you have to get a development env running


### How do I get set up? ###

Install the virtualenv using this command(If you have not installed virtualenv yet.)

```ssh
$ [sudo] pip install virtualenv
```


Create a directory using the following command from your terminal

```ssh
$ [sudo] mkdir BengaliDocumentSummarizer
```


Switch to BengaliDocumentSummarizer directory

```ssh
$ cd BengaliDocumentSummarizer
```


After then create virtual env file by the following command from your terminal

```ssh
$ virtualenv -p python3 venv
```


If you create virtual env file successfully on your development machine then run this command

```ssh
$ source venv/bin/activate
```

And clone the repo

```ssh
$ git clone https://github.com/RohanPatel593/Bengali-Text-Summarization .
```

Install required packages by running the following command
```ssh
$ pip install -r requirements.txt
```

Its time to run the following command
```ssh
$ python main.py
```

Now you have a local server url. Visit the [http://127.0.0.1:8080/](http://127.0.0.1:8080/)
```ssh
 * Running on http://127.0.0.1:8080/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 285-251-887
 ```

