---
title: Saelos API Reference

language_tabs:
- bash
- javascript
- php

includes:

search: true

toc_footers:
- <a href='http://github.com/mpociot/documentarian'>Documentation Powered by Documentarian</a>
---
<!-- START_INFO -->
# Info

Welcome to the Saelos API reference.
[Get Postman Collection](http://saelos.test/docs/collection.json)

<!-- END_INFO -->

#Activities

Interact with activities.
<!-- START_d6afe2a16485b62953e94ffdcef28f5f -->
## Fetching a filtered activity list.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/activities" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/activities",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/activities`

`HEAD api/v1/activities`


<!-- END_d6afe2a16485b62953e94ffdcef28f5f -->

<!-- START_33aef576e6d971e2ba91dd3d8403d390 -->
## Save a new Activity

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/activities" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/activities",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/activities`


<!-- END_33aef576e6d971e2ba91dd3d8403d390 -->

<!-- START_2d841ea22240d81b5beadfec016eb05c -->
## Fetch a single Activity

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/activities/{activity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/activities/{activity}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/activities/{activity}`

`HEAD api/v1/activities/{activity}`


<!-- END_2d841ea22240d81b5beadfec016eb05c -->

<!-- START_66e6c51c201a5a8ca254ce9e8e8a63a9 -->
## Update an existing Activity

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/activities/{activity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/activities/{activity}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/activities/{activity}`

`PATCH api/v1/activities/{activity}`


<!-- END_66e6c51c201a5a8ca254ce9e8e8a63a9 -->

<!-- START_a428814a3c351226a73456c3b41d2a39 -->
## Delete an activity

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/activities/{activity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/activities/{activity}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/activities/{activity}`


<!-- END_a428814a3c351226a73456c3b41d2a39 -->

#Companies

Interact with Companies
<!-- START_cca2c58fd8ac8df724967dd7606ddf6a -->
## Fetching a filtered Company list.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/companies" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/companies`

`HEAD api/v1/companies`


<!-- END_cca2c58fd8ac8df724967dd7606ddf6a -->

<!-- START_7be8cb2d15a57d2062ece90d5b8f8269 -->
## Save a new Company

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/companies" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/companies`


<!-- END_7be8cb2d15a57d2062ece90d5b8f8269 -->

<!-- START_e89f2c83d01fbd40254236b3b8dc1d6c -->
## Fetch a single Company

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/companies/{company}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/companies/{company}`

`HEAD api/v1/companies/{company}`


<!-- END_e89f2c83d01fbd40254236b3b8dc1d6c -->

<!-- START_af6a8ef6ec9748b875fe36d6256c40ed -->
## Update an existing Company

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/companies/{company}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/companies/{company}`

`PATCH api/v1/companies/{company}`


<!-- END_af6a8ef6ec9748b875fe36d6256c40ed -->

<!-- START_02c1ebf9f4df1c10bbf4748053f03c8e -->
## Delete a Company

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/companies/{company}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/companies/{company}`


<!-- END_02c1ebf9f4df1c10bbf4748053f03c8e -->

#Company Notes
<!-- START_dd89053575a126109911d41d58dfca01 -->
## Fetch notes for Company

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/companies/{company}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}/notes",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/companies/{company}/notes`

`HEAD api/v1/companies/{company}/notes`


<!-- END_dd89053575a126109911d41d58dfca01 -->

<!-- START_dcf7bf4dd7c47174b8f03976319abd98 -->
## Save a new Company note.

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/companies/{company}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}/notes",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/companies/{company}/notes`


<!-- END_dcf7bf4dd7c47174b8f03976319abd98 -->

<!-- START_10203456c79c105fc19871e1aa285fb2 -->
## Fetch a single Company note.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/companies/{company}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}/notes/{note}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/companies/{company}/notes/{note}`

`HEAD api/v1/companies/{company}/notes/{note}`


<!-- END_10203456c79c105fc19871e1aa285fb2 -->

<!-- START_1569784c415bdb17157aceb1f11d81f8 -->
## Update an existing Company note.

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/companies/{company}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}/notes/{note}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/companies/{company}/notes/{note}`

`PATCH api/v1/companies/{company}/notes/{note}`


<!-- END_1569784c415bdb17157aceb1f11d81f8 -->

<!-- START_5aff5e655fe287896990d80c7dc2bccf -->
## Delete a Company note.

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/companies/{company}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/companies/{company}/notes/{note}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/companies/{company}/notes/{note}`


<!-- END_5aff5e655fe287896990d80c7dc2bccf -->

#Contact Notes
<!-- START_4e4d1fe5a11fdd7bf6c98dc2ae66c75a -->
## Fetch notes for Contact

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/contacts/{contact}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}/notes",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/contacts/{contact}/notes`

`HEAD api/v1/contacts/{contact}/notes`


<!-- END_4e4d1fe5a11fdd7bf6c98dc2ae66c75a -->

<!-- START_aee3825efb6dff99acdd68bf6c7d7f31 -->
## Save a new Contact note.

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/contacts/{contact}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}/notes",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/contacts/{contact}/notes`


<!-- END_aee3825efb6dff99acdd68bf6c7d7f31 -->

<!-- START_95dcf070ad6bb3dffa7ff475c479931d -->
## Fetch a single Contact note.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/contacts/{contact}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}/notes/{note}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/contacts/{contact}/notes/{note}`

`HEAD api/v1/contacts/{contact}/notes/{note}`


<!-- END_95dcf070ad6bb3dffa7ff475c479931d -->

<!-- START_60c7441b70ccc6ace8658a6d596ea64c -->
## Update an existing Contact note.

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/contacts/{contact}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}/notes/{note}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/contacts/{contact}/notes/{note}`

`PATCH api/v1/contacts/{contact}/notes/{note}`


<!-- END_60c7441b70ccc6ace8658a6d596ea64c -->

<!-- START_cb6c94a5520f391985f7a64895ea1e50 -->
## Delete a Contact note.

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/contacts/{contact}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}/notes/{note}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/contacts/{contact}/notes/{note}`


<!-- END_cb6c94a5520f391985f7a64895ea1e50 -->

#Contacts

Interact with Contacts
<!-- START_416a4afc808e2fe5a932b916821dab61 -->
## Get a count of Contacts.

The count returned represents the number of contacts assigned
to the requesting user that are grouped by the given groupBy
request parameter.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/contacts/count" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/count",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/contacts/count`

`HEAD api/v1/contacts/count`


<!-- END_416a4afc808e2fe5a932b916821dab61 -->

<!-- START_b138f0bf0ceb7cebea6a8c6bc4d88770 -->
## Initiate a call to a Contact.

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/contacts/{id}/call" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{id}/call",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/contacts/{id}/call`


<!-- END_b138f0bf0ceb7cebea6a8c6bc4d88770 -->

<!-- START_6a37f3bfbded9adb5fe86f7140c1c719 -->
## Send an sms to a Contact.

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/contacts/{id}/sms" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{id}/sms",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/contacts/{id}/sms`


<!-- END_6a37f3bfbded9adb5fe86f7140c1c719 -->

<!-- START_c83aedb6f25b1d1451f1ab49498f66c6 -->
## Send an email to a Contact.

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/contacts/{id}/email" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{id}/email",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/contacts/{id}/email`


<!-- END_c83aedb6f25b1d1451f1ab49498f66c6 -->

<!-- START_6fa2906e9ce360ed0313ef6d7e27c771 -->
## Fetching a filtered Contact list.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/contacts" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/contacts`

`HEAD api/v1/contacts`


<!-- END_6fa2906e9ce360ed0313ef6d7e27c771 -->

<!-- START_47c2efeaf62c42ca6aab8e676b494b40 -->
## Save a new Contact

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/contacts" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/contacts`


<!-- END_47c2efeaf62c42ca6aab8e676b494b40 -->

<!-- START_7a85d1ff3a79f9a576c27f1f95133694 -->
## Fetch a single Contact

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/contacts/{contact}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/contacts/{contact}`

`HEAD api/v1/contacts/{contact}`


<!-- END_7a85d1ff3a79f9a576c27f1f95133694 -->

<!-- START_9aec7381d4dd89e68a9ff728678d8b21 -->
## Update an existing Contact.

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/contacts/{contact}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/contacts/{contact}`

`PATCH api/v1/contacts/{contact}`


<!-- END_9aec7381d4dd89e68a9ff728678d8b21 -->

<!-- START_6edc54ea34dd384c52c2ab85854ca8a2 -->
## Delete a Contact

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/contacts/{contact}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/contacts/{contact}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/contacts/{contact}`


<!-- END_6edc54ea34dd384c52c2ab85854ca8a2 -->

#Fields

Interact with core &amp; custom fields.
<!-- START_13c94a2212fdb6fa40ffee94aa94833f -->
## Fetching a filtered Field list.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/fields" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/fields",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/fields`

`HEAD api/v1/fields`


<!-- END_13c94a2212fdb6fa40ffee94aa94833f -->

<!-- START_dc97eb3c36c4ca194360e61af62c5486 -->
## Save a new Field

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/fields" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/fields",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/fields`


<!-- END_dc97eb3c36c4ca194360e61af62c5486 -->

<!-- START_52e2bdbabcd4530f853b3124f20cf135 -->
## Fetch a single Field

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/fields/{field}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/fields/{field}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/fields/{field}`

`HEAD api/v1/fields/{field}`


<!-- END_52e2bdbabcd4530f853b3124f20cf135 -->

<!-- START_98936d3b61a34154ee5cb19b06a8324b -->
## Update an existing Field

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/fields/{field}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/fields/{field}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/fields/{field}`

`PATCH api/v1/fields/{field}`


<!-- END_98936d3b61a34154ee5cb19b06a8324b -->

<!-- START_9f7c65d9807532feeefaf0dd3ecf1015 -->
## Delete a Field

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/fields/{field}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/fields/{field}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/fields/{field}`


<!-- END_9f7c65d9807532feeefaf0dd3ecf1015 -->

#Opportunities

Interact with Opportunities
<!-- START_5eeb7ae43d45cf1f25a2e30f1374708b -->
## Fetching a filtered Opportunities list.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/opportunities" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/opportunities`

`HEAD api/v1/opportunities`


<!-- END_5eeb7ae43d45cf1f25a2e30f1374708b -->

<!-- START_4e47ad5f0c2219554dadfb51b2fdbedc -->
## Save a new Opportunity

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/opportunities" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/opportunities`


<!-- END_4e47ad5f0c2219554dadfb51b2fdbedc -->

<!-- START_d74249b9a67d626b51f1364fb14f3634 -->
## Fetch a single Opportunity

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/opportunities/{opportunity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/opportunities/{opportunity}`

`HEAD api/v1/opportunities/{opportunity}`


<!-- END_d74249b9a67d626b51f1364fb14f3634 -->

<!-- START_a6354cf07a11e6b4c138a7144f3fc897 -->
## Update an existing Opportunity

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/opportunities/{opportunity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/opportunities/{opportunity}`

`PATCH api/v1/opportunities/{opportunity}`


<!-- END_a6354cf07a11e6b4c138a7144f3fc897 -->

<!-- START_6d2057c58f2f256e101fe5a3250aa4f2 -->
## Delete an Opportunity

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/opportunities/{opportunity}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/opportunities/{opportunity}`


<!-- END_6d2057c58f2f256e101fe5a3250aa4f2 -->

#Opportunity Notes
<!-- START_a449f01c1ac73937ca8f2a0458b89e71 -->
## Fetch notes for Opportunity

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/opportunities/{opportunity}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}/notes",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/opportunities/{opportunity}/notes`

`HEAD api/v1/opportunities/{opportunity}/notes`


<!-- END_a449f01c1ac73937ca8f2a0458b89e71 -->

<!-- START_5c94ae37e9210e38b549d3f8c4a296ff -->
## api/v1/opportunities/{opportunity}/notes

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/opportunities/{opportunity}/notes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}/notes",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/opportunities/{opportunity}/notes`


<!-- END_5c94ae37e9210e38b549d3f8c4a296ff -->

<!-- START_1080df27a5df36e555c5fcd9b8258fdd -->
## Fetch a single Opportunity note.

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/opportunities/{opportunity}/notes/{note}`

`HEAD api/v1/opportunities/{opportunity}/notes/{note}`


<!-- END_1080df27a5df36e555c5fcd9b8258fdd -->

<!-- START_b99894f177351245da6f44f490d7b37a -->
## api/v1/opportunities/{opportunity}/notes/{note}

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/opportunities/{opportunity}/notes/{note}`

`PATCH api/v1/opportunities/{opportunity}/notes/{note}`


<!-- END_b99894f177351245da6f44f490d7b37a -->

<!-- START_7a3a4f810b6c3a54ec62cc8b277ae692 -->
## api/v1/opportunities/{opportunity}/notes/{note}

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/opportunities/{opportunity}/notes/{note}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/opportunities/{opportunity}/notes/{note}`


<!-- END_7a3a4f810b6c3a54ec62cc8b277ae692 -->

#Roles

Interact with Roles
<!-- START_d97fba8dbd0d0033960fdc6a25fca8d9 -->
## Fetching Roles

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/roles" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/roles",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/roles`

`HEAD api/v1/roles`


<!-- END_d97fba8dbd0d0033960fdc6a25fca8d9 -->

<!-- START_5f753b2bffb6b34b6136ddfe1be7bcce -->
## Save a new Role

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/roles" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/roles",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/roles`


<!-- END_5f753b2bffb6b34b6136ddfe1be7bcce -->

<!-- START_f47a034257a009b731160db044157715 -->
## Fetch a single Role

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/roles/{role}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/roles/{role}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/roles/{role}`

`HEAD api/v1/roles/{role}`


<!-- END_f47a034257a009b731160db044157715 -->

<!-- START_81ac9047f8db2b92092c5a7f13e5d28d -->
## Update an existing Role

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/roles/{role}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/roles/{role}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/roles/{role}`

`PATCH api/v1/roles/{role}`


<!-- END_81ac9047f8db2b92092c5a7f13e5d28d -->

<!-- START_04c524fc2f0ea8c793406426144b4c71 -->
## Delete a Role

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/roles/{role}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/roles/{role}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/roles/{role}`


<!-- END_04c524fc2f0ea8c793406426144b4c71 -->

#Stages

Interact with Stages
<!-- START_3f2fa928685f81f632331db4483b1a47 -->
## Build the Stage pipeline

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/stages/pipeline" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages/pipeline",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/stages/pipeline`

`HEAD api/v1/stages/pipeline`


<!-- END_3f2fa928685f81f632331db4483b1a47 -->

<!-- START_25055ffe61132b1c5eace536de14de63 -->
## Fetching Stages

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/stages" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/stages`

`HEAD api/v1/stages`


<!-- END_25055ffe61132b1c5eace536de14de63 -->

<!-- START_2e6018981510d64025747fa68c443d41 -->
## Save a new Stage

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/stages" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/stages`


<!-- END_2e6018981510d64025747fa68c443d41 -->

<!-- START_9bcfde5bf4b04c4e14e06155b8305fbe -->
## Fetch a single Stage

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/stages/{stage}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages/{stage}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/stages/{stage}`

`HEAD api/v1/stages/{stage}`


<!-- END_9bcfde5bf4b04c4e14e06155b8305fbe -->

<!-- START_f59010f3473811158a5bd76142767624 -->
## Update an existing Stage

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/stages/{stage}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages/{stage}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/stages/{stage}`

`PATCH api/v1/stages/{stage}`


<!-- END_f59010f3473811158a5bd76142767624 -->

<!-- START_86be1758a93a65b83dd8bec793d8eb3a -->
## Delete a Stage

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/stages/{stage}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/stages/{stage}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/stages/{stage}`


<!-- END_86be1758a93a65b83dd8bec793d8eb3a -->

#Statuses

Interact with Contact statuses
<!-- START_11414f449ae40808a84c5d604434d487 -->
## Fetching a filtered Status list

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/statuses" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/statuses",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/statuses`

`HEAD api/v1/statuses`


<!-- END_11414f449ae40808a84c5d604434d487 -->

<!-- START_a7ada8c4f6e927f36d1b35bcad64309f -->
## Save a new Status

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/statuses" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/statuses",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/statuses`


<!-- END_a7ada8c4f6e927f36d1b35bcad64309f -->

<!-- START_e568b1d682dbe876ec2706fbc27119ac -->
## Fetch a single Status

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/statuses/{status}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/statuses/{status}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/statuses/{status}`

`HEAD api/v1/statuses/{status}`


<!-- END_e568b1d682dbe876ec2706fbc27119ac -->

<!-- START_0898bd606cefca670cfa33547d02e52d -->
## Update an existing Status

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/statuses/{status}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/statuses/{status}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/statuses/{status}`

`PATCH api/v1/statuses/{status}`


<!-- END_0898bd606cefca670cfa33547d02e52d -->

<!-- START_2d91e3a86a0ac5ddfd01b6ca66016715 -->
## Delete a Status

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/statuses/{status}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/statuses/{status}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/statuses/{status}`


<!-- END_2d91e3a86a0ac5ddfd01b6ca66016715 -->

#Tags

Interact with Tags
<!-- START_bd8d313b1ecd7bb87d3dfc0142d5f0ba -->
## Fetching Tags

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/tags" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/tags",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/tags`

`HEAD api/v1/tags`


<!-- END_bd8d313b1ecd7bb87d3dfc0142d5f0ba -->

<!-- START_630f8bae9314aa07bc76748bf619eb33 -->
## Save a new Tag

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/tags" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/tags",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/tags`


<!-- END_630f8bae9314aa07bc76748bf619eb33 -->

<!-- START_ec790d67c677500385a8b51a869f957d -->
## Fetch a single Tag

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/tags/{tag}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/tags/{tag}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/tags/{tag}`

`HEAD api/v1/tags/{tag}`


<!-- END_ec790d67c677500385a8b51a869f957d -->

<!-- START_bc9cb4c2371521e7e1379696effcfa43 -->
## Update an existing Tag

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/tags/{tag}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/tags/{tag}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/tags/{tag}`

`PATCH api/v1/tags/{tag}`


<!-- END_bc9cb4c2371521e7e1379696effcfa43 -->

<!-- START_a5d0790b7aa15c5f66eac1ae30c9a136 -->
## Delete a Tag

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/tags/{tag}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/tags/{tag}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/tags/{tag}`


<!-- END_a5d0790b7aa15c5f66eac1ae30c9a136 -->

#Teams

Interact with Teams
<!-- START_59b8f9b9e0e46c8d0875e706284aa04b -->
## Fetching Teams

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/teams" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/teams",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/teams`

`HEAD api/v1/teams`


<!-- END_59b8f9b9e0e46c8d0875e706284aa04b -->

<!-- START_9c2019f9d2d308844e1949dfa342b380 -->
## Save a new Team

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/teams" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/teams",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/teams`


<!-- END_9c2019f9d2d308844e1949dfa342b380 -->

<!-- START_71c4e0a785177353e476ae3f53ed8b68 -->
## Fetch a single Team

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/teams/{team}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/teams/{team}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/teams/{team}`

`HEAD api/v1/teams/{team}`


<!-- END_71c4e0a785177353e476ae3f53ed8b68 -->

<!-- START_02dc0adeb714bc1c46bd3cde2c952827 -->
## Update an existing Team

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/teams/{team}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/teams/{team}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/teams/{team}`

`PATCH api/v1/teams/{team}`


<!-- END_02dc0adeb714bc1c46bd3cde2c952827 -->

<!-- START_f6de42238cfe6bcbd84ba30779151c10 -->
## Delete a Team

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/teams/{team}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/teams/{team}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/teams/{team}`


<!-- END_f6de42238cfe6bcbd84ba30779151c10 -->

#Users

Interact with Users
<!-- START_1d0d35454d27d82f519a144cfaa02ec0 -->
## Get Quota Counts

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/users/{id}/count" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users/{id}/count",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/users/{id}/count`

`HEAD api/v1/users/{id}/count`


<!-- END_1d0d35454d27d82f519a144cfaa02ec0 -->

<!-- START_080f3ecebb7bcc2f93284b8f5ae1ac3b -->
## Fetching Users

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/users" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/users`

`HEAD api/v1/users`


<!-- END_080f3ecebb7bcc2f93284b8f5ae1ac3b -->

<!-- START_4194ceb9a20b7f80b61d14d44df366b4 -->
## Save a new User

> Example request:

```bash
curl -X POST "http://saelos.test/api/v1/users" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`POST api/v1/users`


<!-- END_4194ceb9a20b7f80b61d14d44df366b4 -->

<!-- START_b4ea58dd963da91362c51d4088d0d4f4 -->
## Fetch a single User

> Example request:

```bash
curl -X GET "http://saelos.test/api/v1/users/{user}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users/{user}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/users/{user}`

`HEAD api/v1/users/{user}`


<!-- END_b4ea58dd963da91362c51d4088d0d4f4 -->

<!-- START_296fac4bf818c99f6dd42a4a0eb56b58 -->
## Update an existing User

> Example request:

```bash
curl -X PUT "http://saelos.test/api/v1/users/{user}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users/{user}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`PUT api/v1/users/{user}`

`PATCH api/v1/users/{user}`


<!-- END_296fac4bf818c99f6dd42a4a0eb56b58 -->

<!-- START_22354fc95c42d81a744eece68f5b9b9a -->
## Delete a User

> Example request:

```bash
curl -X DELETE "http://saelos.test/api/v1/users/{user}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://saelos.test/api/v1/users/{user}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

```php
PHP STUFF WITH GUZZLE
```


### HTTP Request
`DELETE api/v1/users/{user}`


<!-- END_22354fc95c42d81a744eece68f5b9b9a -->

