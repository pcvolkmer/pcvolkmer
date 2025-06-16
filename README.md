### Modellvorhaben Genomsequenzierung gem. §64e SGB V

Bibliotheken für das Modellvorhaben §64e SGB V

#### DNPM:DIP (MV §64e) MTB DTOs basierend auf dem [DNPM Datenmodell Version 2.1](https://ibmi-ut.atlassian.net/wiki/spaces/DAM/pages/698777783)

Die MTB DTO Projekte sind hierhin umgezogen: [DNPM:DIP](https://github.com/dnpm-dip).

| Language/Platform | Test example JSON |
| -------- | -------- |
| [Java](https://github.com/dnpm-dip/mv64e-mtb-dto-java) (JDK 11 based, uses `java.util.Date` and [Project Lombok](https://projectlombok.org/)) | [![Run Tests](https://github.com/dnpm-dip/mv64e-mtb-dto-java/actions/workflows/test.yml/badge.svg)](https://github.com/dnpm-dip/mv64e-mtb-dto-java/actions/workflows/test.yml) |
| [.NET](https://github.com/dnpm-dip/mv64e-mtb-dto-dotnet) (.NET Standard 2.0, uses `NewtonSoft.Json`) | [![Run Tests](https://github.com/dnpm-dip/mv64e-mtb-dto-dotnet/actions/workflows/test.yml/badge.svg)](https://github.com/dnpm-dip/mv64e-mtb-dto-dotnet/actions/workflows/test.yml) |
| [Go](https://github.com/dnpm-dip/mv64e-mtb-dto-go) | [![Run Tests](https://github.com/dnpm-dip/mv64e-mtb-dto-go/actions/workflows/test.yml/badge.svg)](https://github.com/dnpm-dip/mv64e-mtb-dto-go/actions/workflows/test.yml) |
| [Rust](https://github.com/dnpm-dip/mv64e-mtb-dto-rs) | [![Run Tests](https://github.com/dnpm-dip/mv64e-mtb-dto-rs/actions/workflows/test.yml/badge.svg)](https://github.com/dnpm-dip/mv64e-mtb-dto-rs/actions/workflows/test.yml) |

Getestet wurde jeweils für die [hier beschriebenen synthetischen JSON Daten](https://github.com/KohlbacherLab/dnpm-dip-api-gateway/blob/main/app/controllers/README.md).

Siehe auch: [KohlbacherLab/DNPM:DIP-API-Gateway](https://github.com/KohlbacherLab/dnpm-dip-api-gateway)


#### DNPM:DIP (MV §64e) Rare Disease DTOs basierend auf dem [Datenmodell SE:dip](https://ibmi-ut.atlassian.net/wiki/spaces/DRD/pages/1474938)

| Language/Platform | Test example JSON |
| -------- | -------- |
| [Java](https://github.com/pcvolkmer/mv64e-rd-dto-java) (JDK 11 based, uses `java.util.Date`) | [![Run Tests](https://github.com/pcvolkmer/mv64e-rd-dto-java/actions/workflows/test.yml/badge.svg)](https://github.com/pcvolkmer/mv64e-rd-dto-java/actions/workflows/test.yml) |
| [.NET](https://github.com/pcvolkmer/mv64e-rd-dto-dotnet) (.NET Standard 2.0, uses `NewtonSoft.Json`) | [![Run Tests](https://github.com/pcvolkmer/mv64e-rd-dto-dotnet/actions/workflows/test.yml/badge.svg)](https://github.com/pcvolkmer/mv64e-rd-dto-dotnet/actions/workflows/test.yml) |

#### Genomrechenzentrum-Metadaten (MV §64e) DTOs basierend auf dem [GRZ Metadaten-Schema 1.1.7](https://github.com/BfArM-MVH/MVGenomseq_GRZ/blob/main/GRZ/grz-schema.json)

| Language/Platform | Test example JSON |
| -------- | -------- |
| [Java](https://github.com/pcvolkmer/mv64e-grz-dto-java) (JDK 11 based, uses `java.util.Date`) | [![Run Tests](https://github.com/pcvolkmer/mv64e-grz-dto-java/actions/workflows/test.yml/badge.svg)](https://github.com/pcvolkmer/mv64e-grz-dto-java/actions/workflows/test.yml) |
| [.NET](https://github.com/pcvolkmer/mv64e-grz-dto-dotnet) (.NET Standard 2.0, uses `NewtonSoft.Json`) | [![Run Tests](https://github.com/pcvolkmer/mv64e-grz-dto-dotnet/actions/workflows/test.yml/badge.svg)](https://github.com/pcvolkmer/mv64e-grz-dto-dotnet/actions/workflows/test.yml) |

### Alle Projekte

Eine Übersicht über alle Projekte gibt es hier: https://github.com/pcvolkmer?tab=repositories
