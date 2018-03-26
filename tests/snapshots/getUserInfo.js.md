# Snapshot report for `tests/getUserInfo.js`

The actual snapshot is saved in `getUserInfo.js.snap`.

Generated by [AVA](https://ava.li).

## #_getUserInfoFromPage fails for multi-page without pageId

> Snapshot 1

    Error {
      message: '_getUserInfoFromPage must be used with a pageId param',
    }

## #getUserInfo fails for multi-page bot

> Snapshot 1

    Error {
      message: 'can\'t use getUserInfo when using botmaster-messenger with multiple pages. use _getUserInfoFromPage instead',
    }

## #getUserInfo works for multi-page with pageId

> Snapshot 1

    {
      first_name: 'John-David',
      gender: 'male',
      id: '970771109681287',
      last_name: 'Wuarin',
      locale: 'en_US',
      timezone: 1,
    }