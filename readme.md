# Meetup OAuth2 Client Provider [![Build Status](https://travis-ci.org/howlowck/meetup-oauth2-provider.svg?branch=master)](https://travis-ci.org/howlowck/meetup-oauth2-provider) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/howlowck/meetup-oauth2-provider/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/howlowck/meetup-oauth2-provider/?branch=master)

This package is made for the [League's OAuth2 Client](https://github.com/thephpleague/oauth2-client).

## Install
From command line:
`composer require howlowck/meetup-oauth2-provider`

## To Instantiate a Provider  

```php
$provider =  new \Howlowck\OAuth2\Client\Provider\Meetup(array(
    'clientId'  =>  'YOUR_CONSUMER_KEY',
    'clientSecret'  =>  'YOUR_CONSUMER_SECRET',
    'redirectUri' => 'your-redirect-url',
    'scopes' => array('basic'),
));
```

## Notes
For more consumption details, please refer to the readme on [League's OAuth2 Client](https://github.com/thephpleague/oauth2-client).

[More info about Meetup's OAuth2 Specs](http://www.meetup.com/meetup_api/auth/#oauth2)
