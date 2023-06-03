# Resend with Go

This example shows how to use Resend with [Go](https://go.dev).

## Prerequisites

To get the most out of this guide, you’ll need to:

* [Create an API key](https://resend.com/api-keys)
* [Verify your domain](https://resend.com/domains)

## Instructions

1. Set your RESEND_API_KEY environment variable with: `export RESEND_API_KEY="re_123456789"`

2. Initialize your go module with:

`go mod init example.com/example`

3. Install dependencies:

```sh
go get github.com/resendlabs/resend-go
```

4. Execute the following command:

```sh
go run index.go
```

## License

MIT License