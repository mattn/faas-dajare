# faas-dajare

サーバレス だじゃれ API

## Usage

```
$ curl -s http://your-openfaas-server.com/function/dajare
{
  "text": "「このオランダの本、誰の？」「おらんだ」"
}
```

## Installation

```
$ faas-cli build -f ./stack.yml 
$ faas-cli push -f ./stack.yml 
$ faas-cli deploy -f ./stack.yml -e DATABASE_URL='postgres://...'
```

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)
