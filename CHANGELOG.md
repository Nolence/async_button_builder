## [2.0.2-nullsafety.7] - 2021-02-12
Added a typedef in place of inline type on function. Added doc to `builder` field

## [2.0.2-nullsafety.6] - 2021-02-09
Renamed Union classes to match that of factory constructor name (Should not be breaking).

## [2.0.2-nullsafety.5] - 2021-02-01
Removed example integration test

## [2.0.2-nullsafety.4] - 2021-01-26
Adds tests and test coverage. Adds on dispose to cancel timer.

## [2.0.2-nullsafety.3] - 2021-01-25
Removes dangling controller and cleans up main code up a bit

## [2.0.2-nullsafety.2] - 2021-01-25
Fixes wrong image path

## [2.0.1-nullsafety.2] - 2021-01-25
Renames fields to better match standards of other buttons. 

## [2.0.0-dev.1] - 2021-01-25

Breaking. Replaces the fourth argument with a sealed union that better allows for directly managing states, removes unnecessary arguments such as padding, adds transition builders for custom transitions. Currently still includes AnimatedSize.

## [1.0.0-nullsafety.0] - 2021-01-12

Breaking. Adds a fourth argument of loading to the builder. This removes the value notifier that was difficult or confusing to manage in actual usage in my use cases. The argument isLoading is now a `bool`. This also adds a `disabled` field in order to set that on construction.

## [0.1.0-nullsafety.0] - 2021-01-12

Replaces the bool type of isLoading for a ValueNotifier<bool>.

## [0.0.1-nullsafety.2] - 2021-01-12

Adds analysis options and removes unnecessary typedef

## [0.0.1-nullsafety.1] - 2021-01-12

Adds docs to parameters and removes use of unnecessary undescore internal variables.

## [0.0.1-nullsafety.0] - 2021-01-11

Holds basic builder AsyncButtonBuilder. No tests yet. NNBD is supported


## [2.0.7] - 2021-01-12

Have a stable version for users not on beta constraint
