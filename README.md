# ![LOGO](logo.png) They Said So Quotes **flow**ground Connector

## Description

A generated **flow**ground connector for the They Said So Quotes API (version 2.1).

Generated from: https://api.apis.guru/v2/specs/quotes.rest/2.1/swagger.json<br/>
Generated at: 2019-05-07T17:43:46+03:00

## API Description

 They Said So Quotes API offers a complete feature rich REST API access to its quotes platform.  This is the documentation for the world famous [quotes API](https://theysaidso.com/api).  If you are a subscriber and you are trying this from a console add 'X-TheySaidSo-Api-Secret' header and add your api key as the header value. You can test and play with the API right here on this web page. For using the private end points and subscribing to the API please visit https://theysaidso.com/api.

## Authorization

This API does not require authorization.

## Actions

### Gets `Quote of the Day`.<br/>
> Optional `category` param determines<br/>
> the category of returned quote of the day

*Tags:* `qod`

#### Input Parameters
* `category` - _optional_ - QOD Category
* `X-TheySaidSo-Api-Secret` - _optional_ - API Key

### Gets a list of `Quote of the Day` Categories.

*Tags:* `qod`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _optional_ - API Key

### Delete a qshow.

*Tags:* `qshow`

#### Input Parameters
* `id` - _required_ - Qshow ID
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Gets a details about a qshow.

*Tags:* `qshow`

#### Input Parameters
* `id` - _required_ - Qshow ID
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Update an existing qshow.

*Tags:* `qshow`

#### Input Parameters
* `id` - _required_ - Qshow ID
* `title` - _optional_ - Qshow title
* `description` - _optional_ - Qshow description
* `tags` - _optional_ - Tags for the qshow
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Create and add a new qshow to your private collection.

*Tags:* `qshow`

#### Input Parameters
* `title` - _required_ - Qshow title
* `description` - _optional_ - Qshow description
* `tags` - _optional_ - Tags for the qshow
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Get the list of Qshows in They Said So platform.

*Tags:* `qshow`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at
* `public` - _optional_ - Should include public qshows or not in the list

### Get the quotes in a given Qshow.

*Tags:* `qshow`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `id` - _required_ - Qshow ID

### Add a quote to a given Qshow.

*Tags:* `qshow`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `id` - _required_ - Qshow ID
* `quoteid` - _required_ - Quote ID to add the qshow collection

### Remove a quote to a given Qshow.

*Tags:* `qshow`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `id` - _required_ - Qshow ID
* `quoteid` - _required_ - Quote ID to remove from the qshow collection

### Delete a quote. The user needs to be the owner of the quote to be able to delete it.

*Tags:* `quote`

#### Input Parameters
* `id` - _required_ - Quote ID
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Gets a `Quote` with a given `id`.

*Tags:* `quote`

#### Input Parameters
* `id` - _optional_ - Quote ID
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Update a quote

*Tags:* `quote`

#### Input Parameters
* `id` - _required_ - Quote ID
* `quote` - _optional_ - Quote
* `author` - _optional_ - Quote Author
* `tags` - _optional_ - Comma Separated tags
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Add a new quote to your private collection.

*Tags:* `quote`

#### Input Parameters
* `quote` - _required_ - Quote
* `author` - _optional_ - Quote Author
* `tags` - _optional_ - Comma Separated tags
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Gets a list of author names in the system.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at

### Gets a list of `Quote` Categories.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at

### Gets a Random Quote image. Optional `category` param determinesthe category of quote used in the image. Optional `author` param gets the quote image of a given author.

*Tags:* `image`

#### Input Parameters
* `category` - _optional_ - Quote Category
* `author` - _optional_ - Quote Author
* `private` - _optional_ - Should search private collection. Default searches public image collection.
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Get the list of quotes in your private collection.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at

### Gets a `Random Quote`. When you are in a hurry this is what you call to get a random famous quote.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Search for a `Quote` in They Said So platform. Optional `category` , `author`, `minlength`, `maxlength` params determines the filters applied while searching for the quote.

*Tags:* `quote`

#### Input Parameters
* `category` - _optional_ - Quote Category
* `author` - _optional_ - Quote Author
* `minlength` - _optional_ - Quote minimum Length
* `maxlength` - _optional_ - Quote maximum Length
* `query` - _optional_ - keyword to search for in the quote
* `private` - _optional_ - Should search private collection? Default searches public collection.
* `X-TheySaidSo-Api-Secret` - _required_ - API Key

### Add a tag to a given Quote.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `id` - _required_ - Quote ID
* `tags` - _required_ - Comma Separated tags

### Remove a tag from a given quote.

*Tags:* `quote`

#### Input Parameters
* `X-TheySaidSo-Api-Secret` - _required_ - API Key
* `id` - _required_ - Quote ID
* `tags` - _required_ - Comma Separated tags

## License

**flow**ground :- Telekom iPaaS / quotes-rest-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
