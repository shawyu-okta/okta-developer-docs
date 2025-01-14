To use the sample applications, clone the [samples-golang](https://github.com/okta/samples-golang) repository to your local directory. You run the sample app later after you [set the configuration values](/docs/guides/oie-embedded-common-download-setup-app/-/main/#set-the-configuration-values).

To checkout or contribute to the SDK source code, clone the [okta-idx-golang](https://github.com/okta/okta-idx-golang) repository to your local directory, make your changes, and submit pull requests.

There are two main repositories for the embedded SDK and sample applications:

* [okta-idx-golang](https://github.com/okta/okta-idx-golang) &mdash; enables Golang projects to use Okta as an OAuth 2.0 and OpenID Connect provider. The SDK communicates with the Okta Identity Engine to authenticate and register users.

* [samples-golang](https://github.com/okta/samples-golang) &mdash; contains sample applications that demonstrate the various use cases supported by the embedded SDK:

  * **`samples-golang/identity-engine/embedded-auth-with-sdk`** &mdash; sample application that uses the embedded SDK to authenticate the user

  * **`samples-golang/identity-engine/embedded-sign-in-widget`** &mdash; sample application that uses the embedded Sign-In Widget to authenticate the user
