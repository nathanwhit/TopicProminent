ARCHS = arm64 armv7 armv7s
include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = TopicProminentPrefs
TopicProminentPrefs_FILES = TPPRootListController.m
TopicProminentPrefs_INSTALL_PATH = /Library/PreferenceBundles
TopicProminentPrefs_FRAMEWORKS = UIKit
TopicProminentPrefs_PRIVATE_FRAMEWORKS = Preferences
# TopicProminentPrefs_CFLAGS = -fobjc-arc


include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/TopicProminentPrefs.plist$(ECHO_END)
