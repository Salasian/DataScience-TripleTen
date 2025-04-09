# Data description

## Technological process

- Rougher feed: raw material
- Rougher additions: flotation reagents: xanthate, sulfate, depressant
  - Xanthate: flotation promoter or activator
  - Sulfate: sodium sulfide for this particular process
  - Depressant: sodium silicate
- Rougher process: flotation
- Rougher tails: product residues
- Float banks: flotation facility
- Cleaner process: purification
- Rougher Au: rougher gold concentrate
- Final Au: final gold concentrate

## Stage parameters

- air amount: air volume
- fluid levels
- feed size: feed particle size
- feed rate

## Feature designation

This is how the features are named:

[stage]. [parameter_type]. [parameter_name]

Example: rougher.input.feed_ag

Possible values for [stage]:

- rougher: flotation
- primary_cleaner: primary purification
- secondary_cleaner: secondary purification
- final: final characteristics

Possible values for [parameter_type]:

- input: raw material parameters
- output: product parameters
- state: parameters characterizing the current state of the stage
- calculation: calculation characteristics

## Recovery

On the recovery process the variables displayed have the next definitions:

- C: the proportion of gold in the concentrate just after flotation (for rougher concentrate recovery)/after purification (for final concentrate recovery).
- F: the proportion of gold in the feed before flotation (for rougher concentrate recovery)/in the concentrate just after flotation (for final concentrate recovery).
- T: the proportion of gold in the rougher tails just after flotation (for rougher concentrate recovery)/after purification (for final concentrate recovery).
