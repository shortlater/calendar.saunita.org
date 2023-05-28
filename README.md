Generated from https://github.com/onefact/free-url-shortening-on-amazon-s3-on-free-tier/ :)

## [calendar.saunita.org](https://calendar.saunita.org)

Redirection rules in JSON for the Amazon S3 bucket `s3://calendar.saunita.org`:
```
[
    {
        "Condition": {
            "KeyPrefixEquals": "index.html"
        },
        "Redirect": {
            "HostName": "calendar.google.com",
            "Protocol": "https",
            "ReplaceKeyPrefixWith": "calendar/embed?src=9f20c0d7cde4dacb4c7bae245f6a1d787a80bfb61fb5c7a5a87540a48a5740af%40group.calendar.google.com"
        }
    }
]
```
