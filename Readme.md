# Information

This repository provides LineageOS OTA releases

# Requirements

You need to install `hub` ([Instructions](https://stackoverflow.com/questions/21214562/how-to-release-versions-on-github-through-the-command-line/52353299#52353299))

# Usage

`./gen_ota_json.sh $DEVICE $PATH_REPO1 $PATH_REPO2 ...`

where $DEVICE is the codename of your device, and $PATH_REPOx are your repositories you want to include in your changelog
e.g.: 
`./gen_ota_json.sh pine device/xiaomi/pine vendor/xiaomi/pine kernel/xiaomi/pine`
