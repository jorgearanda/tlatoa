# Tlatoa Website

This is the repository for Tlatoa Consulting.

It is a static html site hosted on S3.


## Requirements

```
sudo gem install bundler s3_website
```

`s3_website` will also require having a JDK installed, version 8 or *lower*.


## To build and serve:

No need to run anything! Just open `_site/index.html`.


## To push to S3:

```
s3_website push
```

(But `s3_website.yml` needs to be configured with the right secret `s3` credentials, not included in the repository.)
