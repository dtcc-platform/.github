DTCC Platform is an open-source platform for the exploration of
digital twins for cities. The platform is developed and maintained by
the [Digital Twin Cities Centre](https://dtcc.chalmers.se/) (DTCC)
hosted by Chalmers University of Technology. The aim is to develop an
open modelling, simulation and visualisation platform for interactive
planning, design, and exploration of cities. For more information, please visit [DTCC Platform documentation
](https://platform.dtcc.chalmers.se/).

## Core packages (8)

| Package | `main` | `develop` |
|---------|--------|-----------|
| [dtcc](https://github.com/dtcc-platform/dtcc) | ![dtcc-main](https://github.com/dtcc-platform/dtcc/actions/workflows/ci-build-tests.yml/badge.svg?branch=main) |  |
| [dtcc-common](https://github.com/dtcc-platform/dtcc-common) | ![dtcc-common-main](https://github.com/dtcc-platform/dtcc-common/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-common-develop](https://github.com/dtcc-platform/dtcc-common/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-model](https://github.com/dtcc-platform/dtcc-model) | ![dtcc-model-main](https://github.com/dtcc-platform/dtcc-model/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-model-develop](https://github.com/dtcc-platform/dtcc-model/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-io](https://github.com/dtcc-platform/dtcc-io) | ![dtcc-io-main](https://github.com/dtcc-platform/dtcc-io/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-io-develop](https://github.com/dtcc-platform/dtcc-io/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-data](https://github.com/dtcc-platform/dtcc-data) | ![dtcc-io-main](https://github.com/dtcc-platform/dtcc-io/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-io-develop](https://github.com/dtcc-platform/dtcc-io/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-wrangler](https://github.com/dtcc-platform/dtcc-wrangler) | ![dtcc-wrangler-main](https://github.com/dtcc-platform/dtcc-wrangler/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-wrangler-develop](https://github.com/dtcc-platform/dtcc-wrangler/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-builder](https://github.com/dtcc-platform/dtcc-builder) | ![dtcc-builder-main](https://github.com/dtcc-platform/dtcc-builder/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-builder-develop](https://github.com/dtcc-platform/dtcc-builder/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-viewer](https://github.com/dtcc-platform/dtcc-viewer) | ![dtcc-viewer-main](https://github.com/dtcc-platform/dtcc-viewer/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-viewer-develop](https://github.com/dtcc-platform/dtcc-viewer/actions/workflows/ci.yml/badge.svg?branch=develop) |

| main      | develop  |
|------------------------------------ |--------------------|
| Column 1  Column 2 and 3 and 4      | Column 5  Column 6 |
|------------------------------------ |--------------------|
|   Row 1  |    Row 1  | Row 1        |   Row 1  |   Row 1  |   Row 1  |
|   Row 2  |    Row 2  | Row 2        |   Row 2  |   Row 2  |   Row 2  |
|   Row 3  |    Row 3  | Row 3        |   Row 3  |   Row 3  |   Row 3  |
|   Row 4  |    Row 4  | Row 4        |   Row 4  |   Row 4  |   Row 4  |
|   Row 5  |    Row 5  | Row 5        |   Row 5  |   Row 5  |   Row 5  |
|   Row 6  |    Row 6  | Row 6        |   Row 6  |   Row 6  |   Row 6  |


| Column 1 | Column 2 and 3 and 4      | Column 5 | Column 6 |
|----------|-------------------------- |----------|----------|
|   Row 1  |    Row 1       |   Row 1  |   Row 1  |   Row 1  |
|   Row 2  |    Row 2       |   Row 2  |   Row 2  |   Row 2  |
|   Row 3  |    Row 3       |   Row 3  |   Row 3  |   Row 3  |
|   Row 4  |    Row 4       |   Row 4  |   Row 4  |   Row 4  |
|   Row 5  |    Row 5       |   Row 5  |   Row 5  |   Row 5  |
|   Row 6  |    Row 6       |   Row 6  |   Row 6  |   Row 6  |


| Field  | Description |  Optional | Default |
       | ------ | ----------- | --------- | ------- |
       | manual_entry_indicator | no: is not is allow manual entry <br /> yes: is manual entry enabled| yes | no |
       | amounts | json object containing all transaction amounts <br /> <br /> <table> <tr> <td> Subfield </td> <td> Description </td> <td> Optional </td> <td> Default </td> </tr> <tr> <td> tip </td>  <td> transaction tip amount </td> <td> yes </td> <td> NA </td> </tr> <tr> <td> total </td> <td> equal to Base  Amount + Base amount for  Reduced State Tax + City Tax + State Tax + Reduced State Tax + Tip or Cash back </td> <td> no </td> <td> NA </td> </tr> <tr> <td> cashback </td> <td> cash back amount </td> <td> yes </td> <td> NA </td> </tr> <tr> <td> state_tax </td> <td> State tax amount </td> <td> yes </td> <td> NA </td> </tr> <tr> <td> city_tax </td> <td> City tax amount </td> <td> yes </td> <td> NA </td> </tr> <tr> <td> reduced_tax </td> <td> Reduced state tax amount </td> <td> yes </td> <td> NA </td> </tr> <tr> <td> base_reduced_tax </td> <td> Reduced state tax base amount </td> <td> yes </td> <td> NA </td> </tr> </table> | no | NA |


<table>
   <tr>
    <td colspan="3">main</td>
    <td colspan="3">develop</td>
  </tr>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
    <td>Cell 3</td>
  </tr>
</table>

## Auxiliary packages (2)

| Package | `main` | `develop` |
|---------|--------|-----------|
| [dtcc-infrastructure](https://github.com/dtcc-platform/dtcc-infrastructure) | ![dtcc-infrastructure-main](https://github.com/dtcc-platform/dtcc-infrastructure/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-infrastructure-develop](https://github.com/dtcc-platform/dtcc-infrastructure/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-template](https://github.com/dtcc-platform/dtcc-template) | ![dtcc-template-main](https://github.com/dtcc-platform/dtcc-template/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-template-develop](https://github.com/dtcc-platform/dtcc-template/actions/workflows/ci.yml/badge.svg?branch=develop) |

## Experimental packages (6)

| Repository   | `main` | `develop` |
|--------------|--------|-----------|
| [dtcc-core](https://github.com/dtcc-platform/dtcc-core) | | |
| [dtcc-modules](https://github.com/dtcc-platform/dtcc-modules) | | |
| [dtcc-solar](https://github.com/dtcc-platform/dtcc-solar) | ![dtcc-solar-main](https://github.com/dtcc-platform/dtcc-solar/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-solar-develop](https://github.com/dtcc-platform/dtcc-solar/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-noise](https://github.com/dtcc-platform/dtcc-noise) | ![dtcc-noise-main](https://github.com/dtcc-platform/dtcc-noise/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-noise-develop](https://github.com/dtcc-platform/dtcc-noise/actions/workflows/ci.yml/badge.svg?branch=develop) |
| [dtcc-ue-plugin](https://github.com/dtcc-platform/dtcc-ue-plugin) | | |
| [dtcc-web-viewer](https://github.com/dtcc-platform/dtcc-web-viewer) | | |
| [dtcc-docs](https://github.com/dtcc-platform/dtcc-docs) | ![dtcc-docs-main](https://github.com/dtcc-platform/dtcc-docs/actions/workflows/ci.yml/badge.svg?branch=main) | ![dtcc-docs-develop](https://github.com/dtcc-platform/dtcc-docs/actions/workflows/ci.yml/badge.svg?branch=develop) |

