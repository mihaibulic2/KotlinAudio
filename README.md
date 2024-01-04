# What is this?

This is a fork of the KotlinAudio repo meant specifically for Paced Breathing as it removes all audio focus support to allow playing alongside other media.

See the 'AUDIO FOCUS NOTE' comment in SoundController in the Paced Breathing repo.

# How to modify

1. sync with parent repo
1. make your changes
1. run `./gradlew build` to ensure it builds
1. commit and tag and push to git
1. go to jitpack: https://jitpack.io/#mihaibulic2/KotlinAudio/v2.0.0-PB-release
1. click 'Get It' for the new tag
1. wait for spinner to stop (2-10 min)
1. go to Paced Breathing's app/build.gradle and update the dep with the new tag

NOTE: use `textX` for tags when testing changes. When ready to release use a tag name that matches the parent repo's version along with out suffix (-PB-release)