## Redshift JDBC Driver

The Amazon JDBC Driver for Redshift is a Type 4 JDBC driver that provides database connectivity through the standard JDBC application program interfaces (APIs) available in the Java Platform, Enterprise Editions. The Driver provides access to Redshift from any Java application, application server, or Java-enabled applet.

The driver has many Redshift specific features such as,

* IAM authentication
* IDP authentication
* Redshift specific datatypes support
* External schema support as part of getTables() and getColumns() JDBC API

The driver supports JDBC 4.2 specification.

## Build Driver
### Prerequisites
* JDK8
* Maven 3.x
* Redshift instance connect to.

### Build Artifacts
On Unix system run:
```
build.sh
```
It builds **redshift-jdbc42-{version}.jar** and **redshift-jdbc42-{version}.zip** files under **target** directory. 
The jar file is the Redshift JDBC driver.The zip file contains the driver jar file and all required dependencies files to use AWS SDK for the IDP/IAM features.

### Installation and Configuartion of Driver

See [Amazon Redshift JDBC Driver Installation and Configuration Guide](https://docs.aws.amazon.com/redshift/latest/mgmt/jdbc20_install.html) for more information.

## Report Bugs

See [CONTRIBUTING](CONTRIBUTING.md#Reporting-Bugs/Feature-Requests) for more information.

## Contributing Code Development

See [CONTRIBUTING](CONTRIBUTING.md#Contributing-via-Pull-Requests) for more information.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.

