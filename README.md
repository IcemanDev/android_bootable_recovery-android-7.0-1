# android_bootable_recovery-android-7.0-1

Setting version, time zone and time H24 from BoardConfig.mk

Add inside BoardConfig.mk:

 For Version TWRP
TW_SPECIFIC_VERSION_STR := "3.0.2-x by Github"

 For time Zone Italy
TW_SPECIFIC_TIME_ZONE_VAR := "CET-1CEST,M3.5.0,M10.5.0"
TW_SPECIFIC_TIME_ZONE_GUISEL := "CET-1;CEST,M3.5.0,M10.5.0"

 For H24 hours
TW_SPECIFIC_MILITARY_TIME := "1"
