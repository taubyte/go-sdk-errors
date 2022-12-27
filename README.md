# taubyte/go-sdk-errors

Go-Sdk-Errors is the Taubyte SDK error code directory. 

# Installation
The import path for the package is *github.com/taubyte/go-sdk-errors*.

To install it, run:
```bash
go get github.com/taubyte/go-sdk-errors
```

# Adding New Errors 
Error vars should be name Error+ the cause for error. 
- EX: write failure would be named `ErrorWriteFailed`
Errors specific to a library should also include the library name or type after Error 
- EX: ethereum rpc connection failure would be named `ErrorEthereumRPCFailed`
New errors should be added to the end of the iota ordered constants declaration before `ErrorCap`; if part of a specific library, error should be at the end of that library grouping.

# API documentation
[https://pkg.go.dev/github.com/taubyte/go-sdk-errors](https://pkg.go.dev/github.com/taubyte/go-sdk-errors)

# License
The yaml package is licensed under the GPL v3 licenses.
Please see the LICENSE file for details.


# Help
Find us on our [Discord](https://discord.gg/eKfazxFDf9)


# Maintainers
 - Samy Fodil @samyfodil
 - Aron Jalbuena @arontaubyte
 - Tafseer Khan @tafseer-khan
 - Samuel Stoltenberg @skelouse
