# Lickability Development Best Practices

Code is written for humans. What you write will eventually be compiled away to something unintelligible, so how you choose to write code isn’t for the computer’s benefit. It’s for yourself, both now and later. It’s for any people working on a team with you. And it’s for anyone that stumbles upon your code after you’re long gone.

In order to understand our code better, Lickability employs consistent practices, and to do that we have a defined structure and style to the way we write code. This is intended to be a living repository that will be updated as the Swift language and our experience changes.

If you want to use this, great! If you want to fork it and make changes go ahead. We won’t be accepting issues or pull requests into the repository, as this is not intended to an open source project. This is simply, how we do things.

## Architecture Info

[Architecture Diagram](https://github.com/Lickability/swift-style-guide/blob/master/ArchitectureDiagram.md)

* **M** - [Model](https://github.com/Lickability/swift-style-guide/blob/master/Model.md)
* **V** - [View](https://github.com/Lickability/swift-style-guide/blob/master/View.md)
* **C** - [Controller](https://github.com/Lickability/swift-style-guide/blob/master/Controller.md)
* **VM** - [View Model](https://github.com/Lickability/swift-style-guide/blob/master/ViewModel.md)

### Related Resources
* [Common Controller Types](https://github.com/Lickability/swift-style-guide/blob/master/CommonControllerTypes.md)

## Organizational Info 
* [Assets](https://github.com/Lickability/swift-style-guide/blob/master/Assets.md)
* [Documentation and Comments](https://github.com/Lickability/swift-style-guide/blob/master/DocumentationAndComments.md)
* [Extensions](https://github.com/Lickability/swift-style-guide/blob/master/Extensions.md)
* [Imports](https://github.com/Lickability/swift-style-guide/blob/master/Imports.md)
* [Organization Within a File](https://github.com/Lickability/swift-style-guide/blob/master/OrganizationWithinAFile.md)
* [Project Groups](https://github.com/Lickability/swift-style-guide/blob/master/ProjectGroups.md)

## Technical Info
* [Custom Operators](https://github.com/Lickability/swift-style-guide/blob/master/CustomOperators.md)
* [Default Parameters](https://github.com/Lickability/swift-style-guide/blob/master/DefaultParameters.md)
* [Localization](https://github.com/Lickability/swift-style-guide/blob/master/Localization.md)
* [Interface Builder](https://github.com/Lickability/swift-style-guide/blob/master/InterfaceBuilder.md)
* [Object Communication](https://github.com/Lickability/swift-style-guide/blob/master/Object%20Communication.md)
* [Optionals](https://github.com/Lickability/swift-style-guide/blob/master/Optionals.md)
* [Protocols](https://github.com/Lickability/swift-style-guide/blob/master/Protocols.md)
* [Testing](https://github.com/Lickability/swift-style-guide/blob/master/Testing.md)

## Style

We use [SwiftLint](https://github.com/realm/SwiftLint) for code linting. We avoid making style comments on pull requests wherever possible, instead allowing the linter to catch them while developing. The fully documented `.yml` file we use is located [here](https://github.com/Lickability/swift-style-guide/blob/master/.swiftlint.yml).