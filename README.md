# Adobe Experience Platform test utilities

## About this project

The Adobe Experience Platform test utilities allow you to easily set up test cases for Mobile SDK use cases by providing commonly needed functionality like event capture and assertions, mock network request/response, and state management.

<!-- ### Installation

Integrate the Edge Bridge mobile extension into your app by following the [getting started guide](Documentation/getting-started.md). -->

### Development

**Open the project**

To open and run the project, open the `code/settings.gradle` file in Android Studio

### Development
<!-- 
#### Run the test application

To configure and run the test app for this project, follow the [getting started guide for the test app](Documentation/getting-started-test-app.md). -->

#### Code format

This project uses the code formatting tools [Spotless](https://github.com/diffplug/spotless/tree/main/plugin-gradle) with [Prettier](https://prettier.io/). Formatting is applied when the project is built from Gradle and is checked when changes are submitted to the CI build system.

Prettier requires [Node version](https://nodejs.org/en/download/releases/) 10+
To enable the Git pre-commit hook to apply code formatting on each commit, run the following to update the project's git config `core.hooksPath`:
```
make init
```

## Related Projects

| Project                                                      | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Core extensions](https://github.com/adobe/aepsdk-core-android)                                    | The Mobile Core represents the foundation of the Adobe Experience Platform Mobile SDK. |
| [Edge Network extension](https://github.com/adobe/aepsdk-edge-android) | The Edge Network extension allows you to send data to the Adobe Edge Network from a mobile application. |
| [Adobe Experience Platform Android sample app](https://github.com/adobe/aepsdk-sample-app-android) | Contains a fully implemented Android sample app using the Experience Platform SDKs.                 |

## Documentation

Information about Adobe Experience Platform test utilities' implementation, API usage, and architecture can be found in the [Documentation](Documentation) directory.

Learn more about Mobile SDK extensions in the official [Adobe Experience Platform Mobile SDK documentation](https://developer.adobe.com/client-sdks/documentation/edge-network/).

## Contributing

Contributions are welcomed! Read the [Contributing Guide](./.github/CONTRIBUTING.md) for more information.

## Licensing

This project is licensed under the Apache V2 License. See [LICENSE](LICENSE) for more information.
