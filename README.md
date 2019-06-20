# cardiac.output.R

ABP Waveform Utilities and Cardiac Output Estimators

ABP waveform utilities adapted from code by *Sun et al. 2005.*
Parlikar cardiac output estimator described in *Parlikar et al. 2007.*

## Implemented Utilities

* `wabp` Beat onset detector for ABP waveforms
* `abpfeature` Feature extractor for ABP waveforms
* `jsqi` Signal quality index for ABP waveforms

## Implemented CO Estimators

* `estimate.co.parlikar` Cycle-averaged cardiac output estimator, an implementation of methods described in *Parlikar et al. 2007*