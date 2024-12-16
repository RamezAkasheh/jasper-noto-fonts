# JasperReports Noto Fonts Dependency

This project serves as a dependency
for [JasperReports](https://community.jaspersoft.com/project/jasperreports-library)
to provide access to [Google Noto Fonts](https://fonts.google.com/noto). The
Noto Fonts aim for universal coverage of all writing systems, ensuring that text
is correctly displayed across various scripts.

## Features

- Provides Google Noto Fonts for JasperReports.
- Supports a wide range of languages and scripts.
- Simplifies font management in JasperReports by integrating Noto Fonts as part
  of the library.

## How to Use

1. Add the dependency to your project. If you are using Maven, include the
   following in your `pom.xml`:

2.
```xml
<dependency>
    <groupId>com.ramezakasheh</groupId>
    <artifactId>jasper-noto-fonts</artifactId>
    <version>1.0.0</version>
</dependency>
```

3. Ensure that the fonts are correctly referenced in your JasperReports
   templates. For example, in the `.jrxml` file, specify the Noto Font you want
   to use:

   ```xml
   <font fontName="Noto Sans" />
   ```

4. Build your project and generate reports with universal font support.

## Google Noto Fonts

Google Noto Fonts cover a wide range of writing systems, making them ideal for
multilingual reports. Learn more about the fonts and their available styles at
the [Noto Fonts website](https://fonts.google.com/noto).

## Installation

This library is designed to be integrated seamlessly into a Java project using
JasperReports. Follow the instructions for your build tool (e.g., Maven, Gradle)
to install the dependency.

## License

This project inherits licensing for the Noto Fonts, which are licensed under
the [SIL Open Font License, Version 1.1](https://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web).
Ensure that you comply with the license in your project.

## Contributions

Contributions are welcome! Please feel free to submit issues or create pull
requests to improve this library and expand its compatibility with
JasperReports.

## Author

Created and maintained by `[RamezAkasheh]`.