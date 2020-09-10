# os-scrapy-spage

[![Build Status](https://www.travis-ci.org/cfhamlet/os-scrapy-aio-spage.svg?branch=master)](https://www.travis-ci.org/cfhamlet/os-scrapy-aio-spage)
[![codecov](https://codecov.io/gh/cfhamlet/os-scrapy-aio-spage/branch/master/graph/badge.svg)](https://codecov.io/gh/cfhamlet/os-scrapy-aio-spage)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/os-scrapy-aio-spage.svg)](https://pypi.python.org/pypi/os-scrapy-aio-spage)
[![PyPI](https://img.shields.io/pypi/v/os-scrapy-aio-spage.svg)](https://pypi.python.org/pypi/os-scrapy-aio-spage)


This Project provide [spage](https://github.com/cfhamlet/os-spage) utilities for Scrapy.


## Install

```
pip install os-scrapy-spage
```

## Usage

```
from os_scrapy_spage.utils import spage

spage_bytes = spage(response_or_failure)
```

## Unit Tests

```
sh scripts/test.sh
```

## License

MIT licensed.
