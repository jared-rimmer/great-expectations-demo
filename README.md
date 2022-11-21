# Great Expectations Demo

This repository was put together as an introduction to the great_expectations Python package.

It's designed so that you can follow along using the README and view the completed demo project any time you wish to do so.

## Setting Up A Python Environment Using Pyenv

Creating the environment 

```
pyenv virtualenv great-expectations-demo
pyenv activate great-expectations-demo
```

Installing the dependencies
```
pip install great_expectations
great_expectations --version
```

## Setting Up A Great Expectations Data Context

**N.B.** If you have cloned this repository then you don't need to do this step as the `great_expectations` directory is the output of this process

```
great_expectations init
```

## Adding A Data Source
