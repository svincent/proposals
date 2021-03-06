# [ECMAScript Internationalization API Specification](https://github.com/tc39/ecma402) proposals

 - [Stage 0 Proposals](stage-0-proposals.md)
 - [Finished Proposals](finished-proposals.md)

 [ECMAScript](../README.md) proposals

## Active proposals

Proposals follow [this process document](https://tc39.github.io/process-document/).
This list contains only stage 1 proposals and higher that have not yet been withdrawn/rejected, or become finished.

### Stage 3

| :rocket: | Proposal                                                 | Champion                                        |
|--|------------------------------------------------------------------|-------------------------------------------------|
|  | [Intl.Segmenter: Unicode segmentation in JavaScript][]           | Daniel Ehrenberg                                |

### Stage 2

| :rocket: | Proposal                                                 | Champion                                        |
|--|------------------------------------------------------------------|-------------------------------------------------|
|  | [Intl.RelativeTimeFormat][]                                      | Zibi Braniecki, Daniel Ehrenberg                |
|  | [Intl.ListFormat][]                                              | Zibi Braniecki                                  |
|  | [Exposing Abstract Operations & Locale Info][]                   | Zibi Braniecki                                  |

### Stage 1

| :rocket: | Proposal                                                 | Champion                                        |
|--|------------------------------------------------------------------|-------------------------------------------------|
|  | [Intl.Locale][]                                                  | Zibi Braniecki, Daniel Ehrenberg                |
|  | [Intl.DurationFormat][]                                          | Zibi Braniecki                                  |
|  | [Intl.UnitFormat][]                                              | Zibi Braniecki                                  |
|  | [DateTimeFormat dateStyle & timeStyle][]                         | Zibi Braniecki                                  |

:rocket: means the champion thinks it's ready to advance but has not yet presented to the committee.

### Contributing new proposals

Please see [Contributing to ECMAScript](/CONTRIBUTING.md) for the most up-to-date information on contributing proposals to this standard.

### Onboarding existing proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal that lives outside the TC39 organization:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
  - if you are a TC39 delegate, but not an admin in that organization, please contact @LJHarb
2. @bterlson or @littledan will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work - although Github Pages redirects will be broken (please update your links!).

[Intl.Segmenter: Unicode segmentation in JavaScript]: https://github.com/tc39/proposal-intl-segmenter
[Intl.ListFormat]: https://github.com/zbraniecki/proposal-intl-list-format
[Intl.RelativeTimeFormat]: https://github.com/tc39/proposal-intl-relative-time
[Intl.DurationFormat]: https://github.com/tc39/ecma402/issues/47
[Intl.UnitFormat]: https://github.com/tc39/ecma402/issues/32
[Intl.PluralRules]: https://github.com/tc39/proposal-intl-plural-rules
[Intl.DateTimeFormat.prototype.formatToParts]: https://github.com/tc39/proposal-intl-formatToParts
[Intl.NumberFormat.prototype.formatToParts]: https://github.com/tc39/proposal-intl-formatToParts
[Exposing Abstract Operations & Locale Info]: https://github.com/tc39/ecma402/issues/46
[DateTimeFormat dateStyle & timeStyle]: https://github.com/zbraniecki/proposal-ecma402-datetime-style
[Intl.Locale]: https://github.com/zbraniecki/proposal-intl-locale
