Fibratus
========
[![Build status](https://ci.appveyor.com/api/projects/status/dlvxhc0j026ikcyv?svg=true)](https://ci.appveyor.com/project/rabbitstack/fibratus)
[![Coverage Status](https://codecov.io/gh/rabbitstack/fibratus/branch/master/graph/badge.svg)](https://codecov.io/gh/rabbitstack/fibratus)
[![Code Health](https://landscape.io/github/rabbitstack/fibratus/master/landscape.svg?style=flat)](https://landscape.io/github/rabbitstack/fibratus/master)

**Fibratus** is a tool which is able to capture the most of the Windows kernel activity - process/thread creation and termination, 
file system I/O, registry, network activity, DLL loading/unloading and much more. 
Fibratus has a very simple CLI which encapsulates the machinery to start the kernel event stream collector, 
set kernel event filters or run the lightweight Python modules called **filaments**. You can use filaments to extend Fibratus with your own arsenal of tools.

![fibratus]( https://github.com/rabbitstack/fibratus/blob/master/static/fibratus.png "fibratus" )
![filaments]( https://github.com/rabbitstack/fibratus/blob/master/static/filaments.png "filaments" )

## Requirements

- Python 3.4
- Visual C++ 2012 or above 
- Cython >=0.23.4

## Installation

Install via the pip package manager:

`pip install fibratus`

## Documentation

See the [wiki](https://github.com/rabbitstack/fibratus/wiki/Running).

## Contributing

Please use Github's pull-request model to submit your contributions. Before you send the pull-request you should keep in mind:

* the code has to be in harmony with the **Zen Of Python** principles
* you need to test the code (fibratus uses the `pytest` unit testing framework)
* make sure your code satisfy the **PEP** coding style

## Support

A lot of love and passion is put into Fibratus. If you want to support Fibratus, please consider a donation.

[![Beerpay](https://beerpay.io/rabbitstack/fibratus/badge.svg?style=beer-square)](https://beerpay.io/rabbitstack/fibratus)  [![Beerpay](https://beerpay.io/rabbitstack/fibratus/make-wish.svg?style=flat-square)](https://beerpay.io/rabbitstack/fibratus?focus=wish)
