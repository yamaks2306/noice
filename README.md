# ![Feature graphic](fastlane/metadata/android/en-US/images/featureGraphic.png)

[![Build Status](https://travis-ci.com/ashutoshgngwr/noice.svg?branch=master)](https://travis-ci.com/ashutoshgngwr/noice)
[![codecov](https://codecov.io/gh/ashutoshgngwr/noice/branch/master/graph/badge.svg)](https://codecov.io/gh/ashutoshgngwr/noice)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/67635a43989c4dbcb6c3472375dc1e5f)](https://www.codacy.com/manual/ashutoshgngwr/noice?utm_source=github.com&utm_medium=referral&utm_content=ashutoshgngwr/noice&utm_campaign=Badge_Grade)
[![GitHub tag](https://img.shields.io/github/tag-date/ashutoshgngwr/noice.svg?color=orange&label=release)](https://GitHub.com/ashutoshgngwr/noice/tags/)
[![Releases](https://img.shields.io/badge/android-5.0%2B-blue.svg)][google-play-link]
[![GitHub license](https://img.shields.io/github/license/ashutoshgngwr/noice.svg)](https://github.com/ashutoshgngwr/noice/blob/master/LICENSE)

For a lot of people, a little background noise is helpful to calm down and focus. In some cases, it's also a boost to productivity. Background noise can also help minimize the effects of stress.

Noice is an app that allows you to create your own set of background sounds by mixing clips from environmental sources. Create your perfect surroundings by combining different sounds to drown out distractions so you can focus on your work, or generate serene, peaceful environments that encourage you to fall asleep.

## Download

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="100">][f-droid-link]
[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="100">][google-play-link]

## Features

- 19 recorded noises
- Auto sleep timer
- Make customised mix
- Save your favorite mixes
- Play alongside other music players
- Individual volume control for each noise source
- Offline playback

## Screenshots

|                                                                                      |                                                                                      |                                                                                      |                                                                                      |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| ![Screenshot 1](fastlane/metadata/android/en-US/images/phoneScreenshots/1_en-US.png) | ![Screenshot 2](fastlane/metadata/android/en-US/images/phoneScreenshots/2_en-US.png) | ![Screenshot 3](fastlane/metadata/android/en-US/images/phoneScreenshots/3_en-US.png) | ![Screenshot 4](fastlane/metadata/android/en-US/images/phoneScreenshots/7_en-US.png) |
| ![Screenshot 5](fastlane/metadata/android/en-US/images/phoneScreenshots/4_en-US.png) | ![Screenshot 6](fastlane/metadata/android/en-US/images/phoneScreenshots/5_en-US.png) | ![Screenshot 7](fastlane/metadata/android/en-US/images/phoneScreenshots/6_en-US.png) |                                                                                      |

## Contributing

We welcome contributions of all kinds and sizes. This includes everything from simple bug reports to large features.

### Adding sounds

Feel free to add more sounds to Noice taking the following under consideration.

- Looping sounds should be at least 30 seconds and at most 2 minutes long. These are not hard limits but the goal should be to minimize the ease of recognizing recurring patterns in loops.
- All sounds should be encoded to `mp3` format with the following configuration. I use [Audacity](https://www.audacityteam.org/) for editing audio.
  - **Sample rate**: 44.1 kHz
  - **Bitrate mode**: Preset
  - **Quality**: Standard, 170-210 kbps
  - **Variable Speed**: Fast
  - **Channel Mode**: Stereo

### Workflow

We love GitHub issues!

For small feature requests, an issue first proposing it for discussion or demo implementation in a PR suffice.

For big feature requests, please open an issue to avoid wasting time on a feature that might need reworking.

Small pull requests for things like typos, bug fixes, etc are always welcome.

### DOs

- Let Android Studio do the code formatting.
- Include tests when adding new features.
- When fixing bugs, start with adding a test that highlights how the current behavior is broken. This is not mandatory since it is not always possible/approachable.

### Releases

Noice uses [Travis CI](https://travis-ci.com/github/ashutoshgngwr/noice) for automatically building and pushing releases to Google Play store. All releases happen in two stages.

- First, a candidate release is pushed to beta track on Google Play Store. Git tags for these are marked with format `0.0.0-rc`.
- After ample time, release candidates are released to public track on Google Play Store. Git tags for these are marked with format `0.0.0`.
- F-Droid releases are automatically picked by its builder based on the latest tag. See [metadata](https://gitlab.com/fdroid/fdroiddata/-/blob/master/metadata/com.github.ashutoshgngwr.noice.yml) for more information.

## Privacy Policy

Noice does not collect any kind of data from users. Heck, it doesn't even connect to the Internet.

## License

[MIT](LICENSE)

[google-play-link]: https://play.google.com/store/apps/details?id=com.github.ashutoshgngwr.noice
[f-droid-link]: https://f-droid.org/app/com.github.ashutoshgngwr.noice
