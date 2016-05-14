# TwitterAds
Welcome to TwitterAds; a Python wrapper around the Twitter Ads API.

The Twitter Ads API exposes a bunch of useful resources but interacting with each resource demands a certain familiarity with the API and the Twitter advertising platform. This package aims to ease that requirement where possible.

## Getting started

Getting up and running is extremely easy. In short,
* Clone the repository
* Replace the credentials in `config.py` with your own
* Get some data
```python
>>> import twitter
>>> twitter.get_accounts()
<Twitter Response [OK]>
```

For a more detailed guide on getting up and running, head over to [the online documentation](http://twitter-ads-api.readthedocs.org/en/latest/).

## Contributing and suggesting improvements

Contributions are more than welcome! Simply fork the repository, make your changes locally and open up a pull request for review. You'll find a more detailed guide on this proecdure [here](https://guides.github.com/activities/contributing-to-open-source/).

If you've come across any issues or would like to suggest improvements, please open up an issue [here](https://github.com/jdgillespie91/twitter-ads-api/issues).

## Acknowledgements

This library wouldn't exist without [requests](http://docs.python-requests.org/en/latest/) whose model is the source of inspiration for the one you see here. Not only is the model a good one, the library is so wonderfully written that understanding it is simply a case of reading it.
