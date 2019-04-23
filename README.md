# Spacy on Python 3
## hello spacy world

Tutorial to Setup Python 3's Spacy for Machine Learning Natural Language

## Ensure that you are on Python 3

```python --version```

My system returns, for example:

Python 3.5.2 :: Anaconda 4.1.1 (x86_64)

## Install Spacy

```pip install --user pipenv```

Create Python Virtual Environment

```pyvenv --without-pip /var/www/python/spacy```

```pip install -U --user spacy```

The U flag stands for upgrade to the latest.

User flag is needed for permissions.

"Building wheel for Spacy" will require a lot of time to run

## Install Spacy Module for the Hello World Script

```python -m spacy download en_core_web_sm```

### References

https://spacy.io/usage
