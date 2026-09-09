# Dataset guide

The Excel workbook contains three sheets.

| Sheet | Contents |
|---|---|
| `Actual (2020-2025)` | 2,550 carrier-week observations from November 2020 through July 2025 |
| `Forecasted (2026-2030)` | Carrier-level weekly forecast outputs with lower and upper 80% prediction bounds |
| `Fall2019Baseline` | Carrier-level Fall 2019 passenger, bus-count, and passengers-per-bus baseline values |

## Historical fields

| Field | Meaning |
|---|---|
| `WeekStartDate` | Start date of the reporting week |
| `Carrier` | Bus carrier |
| `BusCount` | Weekly bus departures |
| `PassengerCount` | Weekly passenger departures |
| `PPB` | Passengers per bus |
| `DataSource` | Source-period label supplied with the working data |
| `weekly_avg_snow` | Weekly average snowfall |
| `weekly_avg_temp` | Weekly average temperature |
| `IsHolidayWeek` | Holiday-week indicator |
| `HolidayInWeek` | Holiday name, when applicable |

## Forecast fields

| Field | Meaning |
|---|---|
| `ForecastedPassengers` | Point forecast for weekly passenger volume |
| `Lower80` | Lower bound of the 80% prediction interval |
| `Upper80` | Upper bound of the 80% prediction interval |

The source workbook is retained as an analytical deliverable. Values should be interpreted together with the methodology and limitations described in the final report.

Historical passenger data is attributed to the Port Authority of New York and New Jersey through [New York Open Data](https://data.ny.gov/). Forecasts, engineered variables, and comparison outputs are analytical derivatives created for an academic project and are not official Port Authority projections.
