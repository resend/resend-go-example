> [!IMPORTANT]
> This repository has been consolidated into the new [resend-examples](https://github.com/resend/resend-examples) monorepo, which contains updated examples for all languages and frameworks.
>
> **[View the Go examples here](https://github.com/resend/resend-examples/tree/main/go-resend-examples)**

---


# Resend with Go

This example shows how to use Resend with [Go](https://go.dev) using the [Resend Go SDK](https://github.com/resend/resend-go).

## Prerequisites

To get the most out of this guide, you’ll need to:

* [Create an API key](https://resend.com/api-keys)
* [Verify your domain](https://resend.com/domains)

## Instructions

1. Set your RESEND_API_KEY environment variable by running:

```sh
export RESEND_API_KEY="re_123456789"
```

2. Initialize your go module by running the following command:

```sh
go mod init github.com/resend/resend-go-example
```

3. Install dependencies:

```sh
go get github.com/resend/resend-go/v2
```

4. Execute the following command:

```sh
go run main.go
```

## License

See [LICENSE](LICENSE).
