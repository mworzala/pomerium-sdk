# Pomerium's Go (Golang) SDK

In addition to being able centralize identity-aware access, [Pomerium](https://pomerium.com/) can be used to pass request, and user context to upstream applications as JSON Web Tokens (JWT). 

This packges aims to make verifying that attestation token easier and includes:

- [SDK](https://pkg.go.dev/github.com/pomerium/sdk-go?utm_source=godoc#Verifier)
- [Middleware](https://pkg.go.dev/github.com/pomerium/sdk-go?utm_source=godoc#AddIdentityToRequest) (works with any `http.Handler` compatible router)

For a live example built using this package, see - https://github.com/pomerium/verify.  It is hosted at https://verify.pomerium.com.

For more details, see the docs on [Getting the user's identity](https://www.pomerium.com/docs/topics/getting-users-identity.html#prerequisites). 

## TL;DR show me 

![screenshot](https://github.com/pomerium/sdk-go/blob/master/.github/screenshot.png)
