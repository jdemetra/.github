# JDemetra+

**JDemetra+ is a seasonal adjustment and time series analysis tool** developed by the National Bank of Belgium in collaboration with the Deutsche Bundesbank, Insee and Eurostat in accordance with the [Guidelines of the European Statistical System](https://ec.europa.eu/eurostat/documents/3859598/6830795/KS-GQ-15-001-EN-N.pdf) (ESS).

Since 2015, JDemetra+ has been [officially recommended](https://ec.europa.eu/eurostat/cros/system/files/Jdemetra_%20release.pdf) to the members of the ESS and the European System of Central Banks as the software for seasonal and calendar adjustment of official statistics.

JDemetra+ implements the concepts and algorithms used in the two leading SA methods: TRAMO/SEATS and X-12ARIMA. These methods have been re-engineered using an object-oriented approach, which makes them easier to use, extend and modify.

In addition to seasonal adjustment, JDemetra+ bundles other time series models useful for the production or analysis of economic statistics, such as outlier detection, nowcasting, temporal disaggregation or benchmarking. 

Version 3 offers enhanced seasonal adjustment and trend estimation capabilities, including for high frequency data.

Technically, JDemetra+ is a collection of reusable and extensible Java components, easily accessed through a rich graphical interface. The software is Free and Open Source Software (FOSS) developed under the EUPL licence.

## Repository index

Here's a brief guide to the repositories and what's inside.

### JDemetra+ v3

- [jdplus-main](https://github.com/jdemetra/jdplus-main): **main repository**
- [jdplus-benchmarking](https://github.com/jdemetra/jdplus-benchmarking): benchmarking extensions
- [jdplus-incubator](https://github.com/jdemetra/jdplus-incubator): highfreq, stl and sts extensions
- [jdplus-experimental](https://github.com/jdemetra/jdplus-experimental): experimental extensions
- [jdplus-revisions](https://github.com/jdemetra/jdplus-revisions): revisions extensions
- [jdplus-nowcasting](https://github.com/jdemetra/jdplus-nowcasting): nowcasting extensions
- [jdplus-examples](https://github.com/jdemetra/jdplus-examples): examples of how to use the libraries

### JDemetra+ v2

- [jdemetra-core](https://github.com/jdemetra/jdemetra-core): core libraries
- [jdemetra-app](https://github.com/jdemetra/jdemetra-app): desktop application
- [jwsacruncher](https://github.com/jdemetra/jwsacruncher): tool that re-estimates a workspace multiprocessing
- [rjdemetra](https://github.com/jdemetra/rjdemetra): R interface

## External repositories

### JDemetra+ v3

- [jdplus-sdmx](https://github.com/nbbrd/jdplus-sdmx): SDMX extensions

### JDemetra+ v2

- [jdemetra-dotstat](https://github.com/nbbrd/jdemetra-dotstat): SDMX extensions
- [jdemetra-access](https://github.com/nbbrd/jdemetra-access): Access extensions
- [jdemetra-sas](https://github.com/nbbrd/jdemetra-sas): SAS extensions
- [jdemetra-sa-advanced](https://github.com/nbbrd/jdemetra-sa-advanced): experimental SA methods extensions
- [jdemetra-nowcasting](https://github.com/nbbrd/jdemetra-nowcasting): nowcasting extensions
