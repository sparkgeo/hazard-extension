# OS-C Hazard Core Specification

A hazard is a top-level grouping that captures datasets, indicators, and models. A Hazard contains an array of links objects to other objects and can include additional metadata to describe the contained objects.

See [HAZARD.md](https://github.com/os-climate/hazard/blob/main/HAZARD.md#introduction-to-data-sets-for-hazard-models) for a succinct description of Hazard models

> Introduction to data sets for hazard models
Hazards come in two varieties:
>
> 1. Acute hazards: events, for example heat waves, inundations (floods) and hurricanes, and
>
> 2. Chronic hazards: long-term shifts in climate parameters such as average temperature, sea-level or water stress indices.
>
> See methodology document for more details.
>
> Two important types of model used in the assessment of the vulnerability of an asset (natural or financial) to an acute hazard are:
>
> 1. Event-based models, where the model provides a large number of individual simulated events, actual or plausible, and
>
> 2. Return-period-based models, where the model rather provides the statistic properties of the ensemble of events.

These requriements are fully described in the [core specification](./core-spec.md) and [core schema](./schema/schema.json)

The specification is currently filtered for the following hazard types:

## Allowed Hazard Types

| Hazard Type          |
|----------------------|
| ChronicHeat          |
| AirTemperature       |
| ChronicWind          |
| CoastalInundation    |
| CombinedInundation   |
| Drought              |
| Fire                 |
| Hail                 |
| Hazard               |
| Inundation           |
| PluvialInundation    |
| Precipitation        |
| RiverineInundation   |
| WaterRisk            |
| WaterTemperature     |
| Wind                 |
