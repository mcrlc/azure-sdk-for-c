# Azure Platform Abstraction Layer

## Getting Started

## Hardware Platform

### Implemented with Win32 Library

Azure Win32 Platform abstraction layer (`az_win32`) provides platform-specific implementation for the small set of features that Azure SDK needs, yet they are not available as a part of the C99 standard library. This library follows the Azure SDK Design Guidelines for Embedded C.

### Implemented with POSIX APIs

Azure POSIX Platform abstraction layer (`az_posix`) provides platform-specific implementation for the small set of features that Azure SDK needs, yet they are not available as a part of the C99 standard library. This library follows the Azure SDK Design Guidelines for Embedded C.

### Empty Implementation

Azure empty Platform abstraction layer (`az_noplatform`) provides platform-specific implementation for the small set of features that Azure SDK needs, yet they are not available as a part of the C99 standard library. This library follows the Azure SDK Design Guidelines for Embedded C.

## HTTP Platform

### Azure SDK Transport Policy for Curl

Azure Transport Policy Curl (`az_curl`) provides abstractions, and helpers for communicating with Azure using libcurl in the C programming language. This library follows the Azure SDK Design Guidelines for Embedded C.

The library allows clients to communicate with Azure.

### Azure SDK Empty Transport Policy

Azure Empty Transport Policy (`az_nohttp`) provides an empty stub for the HTTP transport implementation. This library follows the Azure SDK Design Guidelines for Embedded C.

The library allows clients to communicate with Azure.

### Install the Package

TODO

### Authenticate the Client

TODO

### Get Credentials

TODO

### Create Client

TODO

## Key Concepts

TODO

## Examples

TODO

## Troubleshooting

### General

TODO

### Retry Policy

TODO

## Next Steps

### More Sample Code

TODO

### Additional Documentation

TODO

## Contributing

If you'd like to contribute to this library, please read the [contributing guide][azure_sdk_for_c_contributing] to learn more about how to build and test the code.

### License

Azure SDK for Embedded C is licensed under the [MIT][azure_sdk_for_c_license] license.

<!-- LINKS -->
[azure_sdk_for_c_contributing]: https://github.com/Azure/azure-sdk-for-c/blob/master/CONTRIBUTING.md
[azure_sdk_for_c_license]: https://github.com/Azure/azure-sdk-for-c/blob/master/LICENSE
[azure_sdk_for_c_contributing]: https://github.com/Azure/azure-sdk-for-c/blob/master/CONTRIBUTING.md
[azure_sdk_for_c_contributing_developer_guide]: https://github.com/Azure/azure-sdk-for-c/blob/master/CONTRIBUTING.md#developer-guide
[azure_sdk_for_c_contributing_pull_requests]: https://github.com/Azure/azure-sdk-for-c/blob/master/CONTRIBUTING.md#pull-requests
[azure_cli]: https://docs.microsoft.com/cli/azure
[azure_pattern_circuit_breaker]: https://docs.microsoft.com/azure/architecture/patterns/circuit-breaker
[azure_pattern_retry]: https://docs.microsoft.com/azure/architecture/patterns/retry
[azure_portal]: https://portal.azure.com
[azure_sub]: https://azure.microsoft.com/free/
[c_compiler]: https://visualstudio.microsoft.com/vs/features/cplusplus/
[cloud_shell]: https://docs.microsoft.com/azure/cloud-shell/overview
[cloud_shell_bash]: https://shell.azure.com/bash