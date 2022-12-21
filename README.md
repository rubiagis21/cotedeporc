# cotedeporc

## Quotes api with Hanami and Sequel

### Run

```
bundle install
bundle exec rackup
```

### Add a quote

```
curl -v -XPOST http://127.0.0.1:9292/v1/quotes \
  -d 'quote[topic]=youpi' -d 'quote[body]=youpi !!!'
```

### List quotes

```
curl -v http://127.0.0.1:9292/v1/quotes
```

## License

The MIT License

Copyright (c) 2012-2019 Laurent Arnoud <laurent@spkdev.net>
