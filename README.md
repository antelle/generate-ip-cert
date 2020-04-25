# Generate IP Cert

This script generates a self-signed SSL certificate for an IP address.

## Usage

```sh
curl https://raw.githubusercontent.com/antelle/generate-ip-cert/master/generate-ip-cert.sh | bash -
```

This will create two files: `cert.pem` and `key.pem`.

## Motivation

While it's easy to make a self-signed SSL certificate for a hostname, doing it for an IP address
is a bit more complicated. I found several guides on Internet that didn't work for me,
so here's the summary in one script.

Tested only on macOS Catalina.

## License

MIT
