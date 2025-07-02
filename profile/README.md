# JDemetra+

**JDemetra+ is a seasonal adjustment and time series analysis tool** developed by the National Bank of Belgium in collaboration with the Deutsche Bundesbank, Insee and Eurostat in accordance with the [Guidelines of the European Statistical System](https://ec.europa.eu/eurostat/en/web/products-manuals-and-guidelines/w/ks-gq-24-012) (ESS).

[![Static Badge](https://img.shields.io/badge/Desktop_application-8A2BE2)](https://github.com/jdemetra/jdplus-main/releases/latest)
[![Static Badge](https://img.shields.io/badge/R_packages-8A2BE2)](https://github.com/rjdverse)
[![Static Badge](https://img.shields.io/badge/Documentation-8A2BE2)](https://jdemetra-new-documentation.netlify.app/)
[![Static Badge](https://img.shields.io/badge/Blog-8A2BE2)](https://jdemetra-universe-blog.netlify.app/)

Since 2015, JDemetra+ has been [officially recommended](https://github.com/user-attachments/files/17409112/2015-01-21.Jdemetra%2B.release.pdf) to the members of the ESS and the European System of Central Banks as the software for seasonal and calendar adjustment of official statistics.

JDemetra+ implements the concepts and algorithms used in the two leading SA methods: TRAMO/SEATS and X-12ARIMA. These methods have been re-engineered using an object-oriented approach, which makes them easier to use, extend and modify.

In addition to seasonal adjustment, JDemetra+ bundles other time series models useful for the production or analysis of economic statistics, such as outlier detection, nowcasting, temporal disaggregation or benchmarking. 

Version 3 offers enhanced seasonal adjustment and trend estimation capabilities, including for high frequency data.

Technically, JDemetra+ is a collection of reusable and extensible Java components, easily accessed through a rich graphical interface. The software is Free and Open Source Software (FOSS) developed under the [EUPL licence](https://interoperable-europe.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

> [!IMPORTANT]
> JDemetra+ v3 is under active development and improvement, while v2 is in maintenance mode. The v3 has all the features of v2, and it can use v2 workspaces. However, note that the opposite is not true: once a v2 workspace is modified by v3, v2 cannot read it anymore.  
> v2 will reach its end of life in December 2026, which coincides with the end of Java 8's official support.

## Repository index

Here's a brief guide to the repositories and what's inside.

### JDemetra+ v3

| Repository | Description | Latest release |
|---|---|---|
| [jdplus-main](https://github.com/jdemetra/jdplus-main) | **Main repository** | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-main.svg)](https://github.com/jdemetra/jdplus-main/releases/latest) |
| [jdplus-benchmarking](https://github.com/jdemetra/jdplus-benchmarking) | Benchmarking extensions | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-benchmarking.svg)](https://github.com/jdemetra/jdplus-benchmarking/releases/latest) |
| [jdplus-incubator](https://github.com/jdemetra/jdplus-incubator) | Highfreq, stl and sts extensions | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-incubator.svg)](https://github.com/jdemetra/jdplus-incubator/releases/latest) |
| [jdplus-experimental](https://github.com/jdemetra/jdplus-experimental) | Experimental extensions | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-experimental.svg)](https://github.com/jdemetra/jdplus-experimental/releases/latest) |
| [jdplus-revisions](https://github.com/jdemetra/jdplus-revisions) | Revisions extensions | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-revisions.svg)](https://github.com/jdemetra/jdplus-revisions/releases/latest) |
| [jdplus-nowcasting](https://github.com/jdemetra/jdplus-nowcasting) | Nowcasting extensions | [![Download](https://img.shields.io/github/release/jdemetra/jdplus-nowcasting.svg)](https://github.com/jdemetra/jdplus-nowcasting/releases/latest) |
| [jdplus-examples](https://github.com/jdemetra/jdplus-examples) | Examples of how to use the libraries | - |

### JDemetra+ v2

| Repository | Description | Latest release |
|---|---|---|
| [jdemetra-core](https://github.com/jdemetra/jdemetra-core) | Core libraries | [![Download](https://img.shields.io/github/release/jdemetra/jdemetra-core.svg)](https://github.com/jdemetra/jdemetra-core/releases/latest) |
| [jdemetra-app](https://github.com/jdemetra/jdemetra-app) | Desktop application | [![Download](https://img.shields.io/github/release/jdemetra/jdemetra-app.svg)](https://github.com/jdemetra/jdemetra-app/releases/latest) |
| [jwsacruncher](https://github.com/jdemetra/jwsacruncher) | Tool that re-estimates a workspace multiprocessing | [![Download](https://img.shields.io/github/release/jdemetra/jwsacruncher.svg)](https://github.com/jdemetra/jwsacruncher/releases/latest) |
| [rjdemetra](https://github.com/rjdverse/rjdemetra) | R interface | [![Download](https://img.shields.io/github/release/rjdverse/rjdemetra.svg)](https://github.com/rjdverse/rjdemetra/releases/latest) |

## External repositories

### JDemetra+ v3

| Repository | Description | Latest release |
|---|---|---|
| [jdplus-sdmx](https://github.com/nbbrd/jdplus-sdmx) | SDMX extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdplus-sdmx.svg)](https://github.com/nbbrd/jdplus-sdmx/releases/latest) |

### JDemetra+ v2

| Repository | Description | Latest release |
|---|---|---|
| [jdemetra-dotstat](https://github.com/nbbrd/jdemetra-dotstat) | SDMX extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdemetra-dotstat.svg)](https://github.com/nbbrd/jdemetra-dotstat/releases/latest) |
| [jdemetra-access](https://github.com/nbbrd/jdemetra-access) | Access extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdemetra-access.svg)](https://github.com/nbbrd/jdemetra-access/releases/latest) |
| [jdemetra-sas](https://github.com/nbbrd/jdemetra-sas) | SAS extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdemetra-sas.svg)](https://github.com/nbbrd/jdemetra-sas/releases/latest) |
| [jdemetra-sa-advanced](https://github.com/nbbrd/jdemetra-sa-advanced) | Experimental SA methods extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdemetra-sa-advanced.svg)](https://github.com/nbbrd/jdemetra-sa-advanced/releases/latest) |
| [jdemetra-nowcasting](https://github.com/nbbrd/jdemetra-nowcasting) | Nowcasting extensions | [![Download](https://img.shields.io/github/release/nbbrd/jdemetra-nowcasting.svg)](https://github.com/nbbrd/jdemetra-nowcasting/releases/latest) |
