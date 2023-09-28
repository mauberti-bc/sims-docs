---
layout: default
title: Add Species Observations
nav_order: 6
parent: Getting Started
permalink: /docs/getting-started/adding-species-observations
---

# Add Species Observations

You can add Species Observations to describe where and when you saw various species, either during or outside of a formal survey.

### Observations are species counts

Species Observations are explicit counts of species, ideally at a known time and location. If you did not identify the species, you can choose the lowest-ranking taxonomic group that you did confirm, such as a genus or family.

The core parts of a Species Observation include:

- Species or taxon
- Count
- Date and time
- Location

You must enter a taxon and count for every Species Observation, but the date, time, and location are optional. This is because you might not record the time or location of every animal that you observe, either because your Sampling Method doesn't require it or for another reason, like a malfunctioning GPS.

Species Observations without location information will appear on a map with the geometry of their Sampling Location. Similarly, when searching for Species Observations between two dates, you will see Observations with no time information if those records' Sampling Periods overlap the date range that you're searching for.

### Subcounts

You can add details like life stage and sex to a Species Observation, which creates a Subcount. Subcounts describe how many individuals you observed with a specific set of characteristics and let you capture relatedness between observed animals. For instance, an observation of an adult female black bear with two yearlings would be structured as:

- Species Observation: 3 black bears
- Subcount: 1 adult, female
- Subcount: 2 yearlings

### Survey Observations and Incidental Observations

Species Observations are considered _Survey_ Observations if they reference a Sampling Period, Sampling Method, and Sampling Location.
_Incidental_ Observations are Species Observations that do not reference any sampling information.

If you observed a species of interest during a formal survey, even if it was not your target species, you should include it as a Survey Observation with reference to the relevant Sampling Period. Conversely, if you observed a species of interest outside of a formal Survey, such as when travelling between Sampling Locations or on your way home, you should include it as an _Incidental_ Observation.

Unlike Survey Observations, Incidental Observations must have a location and time. Otherwise, Incidental Observations only include a species name and count, which isn't very useful.

<a class="float-left" href="/docs/getting-started/add-animals">
Previous: Add Animals
</a>
<a class="float-right" href="/docs/getting-started/add-telemetry">
Next: Add Telemetry
</a>
