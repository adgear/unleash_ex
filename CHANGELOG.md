# Changelog

<!-- %% CHANGELOG_ENTRIES %% -->

## 1.9.0 - 2023-01-25

* add: Telemetry events for `Unleash.Client` [!28](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/28)
* add: Telemetry events for `Unleash.enabled?` [!29](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/29)
* add: Telemetry events for `Unleash.get_variant` [!30](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/30)
* add: Telemetry events for `Unleash.Repo` [!31](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/31)
* add: Telemetry events for metrics pushed to server [!33](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/33)
* remove: Logger calls [!37](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/36)

Thanks [Jekri Orlina](https://gitlab.com/jekku) and [Sam Hutchings](https://gitlab.com/samhutchings) for telemetry
adoption.


## 1.8.3 - 2022-05-31

* fix: Avoid crash when mojito connect is closed for the metrics client
  [!26](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/26) Thanks [John Bell](https://gitlab.com/johnabell)!
* fix: Feature flag without variants cause FunctionClause Error
  [!25](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/25) Thanks
  [Ulisses Almeida](https://gitlab.com/ulissesalmeida)


## 1.8.2
* fix `Unleash.Metrics.add_metrics` ccrash for unrecorded feature_toggle [!24](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/24) Thanks [calvin-kargo](https://gitlab.com/calvin-kargo)!

## 1.8.1
* fix Unleash.Metrics to provide proper start_link/1 behaviour [!23](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/23) Thanks [calvinsadewa](https://gitlab.com/calvin-kargo)!

## 1.8.0

* Use ETS cache to store features rather than Genserver state
  [!22](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/22) Thanks
  [Maximilien Rothier Bautzer](https://gitlab.com/cachemoi)

## 1.7.2
* Disabled flags should not produce an active variant [!20](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/20) Thanks [Daniel Cooper](https://gitlab.com/danielcooper)

## 1.7.1
* Handle unexpected mojito_response messages [!19](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/19) Thanks [Daniel Cooper](https://gitlab.com/danielcooper)

## 1.7.0
* Also transform the member in a list query [!17](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/17) Thanks [Daniel Cooper](https://gitlab.com/danielcooper)!
* Update mojito to current [!18](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/18) Thanks [Daniel Cooper](https://gitlab.com/danielcooper)!

## 1.6.0
* Add Flexible Rollout Strategy [!12](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/12)
* Support Constraints for Feature Flags [!14](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/14)
* Avoid using Mix.env at runtime [!16](https://gitlab.com/afontaine/unleash_ex/-/merge_requests/16) Thanks [Daniel Cooper](https://gitlab.com/danielcooper)!

## 1.5.0
* Add ability to fetch all feature flag names [decfa826](https://gitlab.com/afontaine/unleash_ex/commit/decfa826fca2d656a61f8e77c29138ea28214473)

## 1.4.1
* Suport Running With Distillery [!10](https://gitlab.com/afontaine/unleash_ex/merge_requests/10) Thanks [Thomas Chandler](https://gitlab.com/thomaschandler)!
* Use cached features when unexpected response received from Unleash server [!11](https://gitlab.com/afontaine/unleash_ex/merge_requests/11) Thanks [Thomas Chandler](https://gitlab.com/thomaschandler)!

## 1.4.0
* Add Support for Capturing Metrics on Variants [!7](https://gitlab.com/afontaine/unleash_ex/merge_requests/7)

## 1.3.1
* Fix Missing Content-Type for Posting Metrics [89d073cf](https://gitlab.com/afontaine/unleash_ex/commit/89d073cf6e507816259c8481b9510c56db672deb)

## 1.3.0
* Fix Variant Serialization to JSON [e5f4fd3c](https://gitlab.com/afontaine/unleash_ex/commit/e5f4fd3cece12810afbe789c122404e9169bd1ef)
* Use Mojito to Pool HTTP Connections [e5f4fd3c](https://gitlab.com/afontaine/unleash_ex/commit/e5f4fd3cece12810afbe789c122404e9169bd1ef)

## 1.2.0
* Add Variant Support [!5](https://gitlab.com/afontaine/unleash_ex/merge_requests/5)
* Fix ETag Usage [f30b80bf](https://gitlab.com/afontaine/unleash_ex/commit/f30b80bf931f56f5de908ca738977c2e540155e4)

## 1.1.0
* Add Optional `Plug` Module [!6](https://gitlab.com/afontaine/unleash_ex/merge_requests/6)

## 1.0.0
* Implement Client Specification Tests [!4](https://gitlab.com/afontaine/unleash_ex/merge_requests/4)

## 0.2.0

* Add E-Tag Caching Support [!1](https://gitlab.com/afontaine/unleash_ex/merge_requests/1)
* Send the Library Version when Registering Client [!2](https://gitlab.com/afontaine/unleash_ex/merge_requests/2)
* Add Checks for a Retry Limit [!3](https://gitlab.com/afontaine/unleash_ex/merge_requests/3)

## 0.1.0

* Initial release

## Unreleased
