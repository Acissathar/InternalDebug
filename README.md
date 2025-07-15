# InternalDebug

Unity Package Manager compliant version of UnityDebug: https://github.com/JoebRogers/UnityDebug

## Description

This is a static `InternalDebug` wrapper class for the `UnityEngine.Debug` class.
Any call from this class will only be present when the build is either a Development Build or build in
Development Mode.

```csharp
InternalDebug.Log("Hello World!"); // Will not run in production builds unlike Debug.Log
```

*Specifically using https://github.com/JoebRogers/UnityDebug/blob/master/src/InternalDebug_NoNamespace.cs*

## Getting Started

### Dependencies

N/A

### Installing

#### Install via git URL

In Package Manager, add https://github.com/Acissathar/InternalDebug.git as a custom gitpackage.

Example:
![image](https://github.com/user-attachments/assets/eb88d6e1-4910-487c-93e6-82f4e274dc1a)

![image](https://github.com/user-attachments/assets/d27e7c76-d30b-4007-8c9b-50ed4a82349f)

#### Source

Refer to original repo: https://github.com/JoebRogers/UnityDebug

## Contact

[@Acissathar](https://twitter.com/Acissathar)

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments
* [JoebRogers](https://github.com/JoebRogers)
  - Thank you for the wrapper!
