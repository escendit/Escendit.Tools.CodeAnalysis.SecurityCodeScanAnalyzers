# NuGet Package: Escendit.Tools.CodeAnalysis.SecurityCodeScanAnalyzers
This NuGet package leverages the power of static code analyzer for .NET
to enforce code quality standards that are tailored to the organization's specific needs.
By default,
the package uses a set of analyzer rules that have been configured to align with the organization's coding practices,
ensuring that our code is always compliant and maintainable.

Key features:

- Utilize Roslyn static code analyzer for .NET for powerful and customizable code analysis
- Defaults suited to the organization's coding practices
- Ensures code compliance and maintainability

## Installation
To install this package, use the NuGet Package Manager Console:

```shell
PM> Install-Package Escendit.Tools.CodeAnalysis.SecurityCodeScanAnalyzers
```
Or you can search for "Escendit.Tools.CodeAnalysis.SecurityCodeScanAnalyzers"
in the NuGet Package Manager UI and install it from there.

## Usage
After installing the package, the MSBuild and .editorconfig properties will be set automatically.
- You can modify the MSBuild properties by updating the values in your .csproj or .vbproj file.
- You can modify the .editorconfig properties by creating .editorconfig file and overriding the default values.

## Configuration

The NuGet package includes the following default rules and severity levels:

| Rule    | Severity | Severity |
|---------|----------|----------|
| SCS0000 | warning  | ⚠️       |
| SCS0001 | warning  | ⚠️       |
| SCS0002 | warning  | ⚠️       |
| SCS0003 | warning  | ⚠️       |
| SCS0004 | warning  | ⚠️       |
| SCS0005 | warning  | ⚠️       |
| SCS0006 | warning  | ⚠️       |
| SCS0007 | warning  | ⚠️       |
| SCS0008 | warning  | ⚠️       |
| SCS0009 | warning  | ⚠️       |
| SCS0010 | warning  | ⚠️       |
| SCS0011 | warning  | ⚠️       |
| SCS0012 | warning  | ⚠️       |
| SCS0013 | warning  | ⚠️       |
| SCS0014 | warning  | ⚠️       |
| SCS0015 | warning  | ⚠️       |
| SCS0016 | warning  | ⚠️       |
| SCS0017 | warning  | ⚠️       |
| SCS0018 | warning  | ⚠️       |
| SCS0019 | warning  | ⚠️       |
| SCS0020 | warning  | ⚠️       |
| SCS0021 | warning  | ⚠️       |
| SCS0022 | warning  | ⚠️       |
| SCS0023 | warning  | ⚠️       |
| SCS0024 | warning  | ⚠️       |
| SCS0025 | warning  | ⚠️       |
| SCS0026 | warning  | ⚠️       |
| SCS0027 | warning  | ⚠️       |
| SCS0028 | warning  | ⚠️       |
| SCS0029 | warning  | ⚠️       |
| SCS0030 | warning  | ⚠️       |
| SCS0031 | warning  | ⚠️       |
| SCS0032 | warning  | ⚠️       |
| SCS0033 | warning  | ⚠️       |
| SCS0034 | warning  | ⚠️       |

To modify the severity level of a rule, you can add the following code to your .editorconfig file:

```editorconfig
dotnet_diagnostic.<Rule>.severity = <Severity>
```

For example, to change the severity level of `SCS9999` to "error", add the following line to your .editorconfig file:

```editorconfig
dotnet_diagnostic.SCS9999.severity = error
```


## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the MIT License. See the LICENSE.txt file for details.
