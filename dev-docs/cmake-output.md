# An output of cmake on Kubuntu 18.04

If it can be useful, this is an output of `cmake` on Kubuntu 18.04:

```
~/krusader-build$ cmake ../krusader -DCMAKE_INSTALL_PREFIX=/usr/ -DCMAKE_C_FLAGS:STRING="-O2 -fPIC" -DCMAKE_CXX_FLAGS:STRING="-O2 -fPIC"
-- The C compiler identification is GNU 7.3.0
-- The CXX compiler identification is GNU 7.3.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Installing in the same prefix as Qt, adopting their path scheme.
-- Looking for __GLIBC__
-- Looking for __GLIBC__ - found
-- Performing Test _OFFT_IS_64BIT
-- Performing Test _OFFT_IS_64BIT - Success
-- Performing Test HAVE_DATE_TIME
-- Performing Test HAVE_DATE_TIME - Success
-- Searching for KF5KIO version 5.23 or newer...
-- Found KF5KIO: /usr/lib/x86_64-linux-gnu/cmake/KF5KIO/KF5KIOConfig.cmake (found version "5.44.0")
-- Found KF5Archive: /usr/lib/x86_64-linux-gnu/cmake/KF5Archive/KF5ArchiveConfig.cmake (found version "5.44.0")
-- Found KF5Bookmarks: /usr/lib/x86_64-linux-gnu/cmake/KF5Bookmarks/KF5BookmarksConfig.cmake (found version "5.44.0")
-- Found KF5Codecs: /usr/lib/x86_64-linux-gnu/cmake/KF5Codecs/KF5CodecsConfig.cmake (found version "5.44.0")
-- Found KF5Completion: /usr/lib/x86_64-linux-gnu/cmake/KF5Completion/KF5CompletionConfig.cmake (found version "5.44.0")
-- Found KF5CoreAddons: /usr/lib/x86_64-linux-gnu/cmake/KF5CoreAddons/KF5CoreAddonsConfig.cmake (found version "5.44.0")
-- Found KF5Config: /usr/lib/x86_64-linux-gnu/cmake/KF5Config/KF5ConfigConfig.cmake (found version "5.44.0")
-- Found KF5DocTools: /usr/lib/x86_64-linux-gnu/cmake/KF5DocTools/KF5DocToolsConfig.cmake (found version "5.44.0")
-- Found Gettext: /usr/bin/msgmerge (found version "0.19.8.1")
-- Found PythonInterp: /usr/bin/python (found version "2.7.15")
-- Found KF5I18n: /usr/lib/x86_64-linux-gnu/cmake/KF5I18n/KF5I18nConfig.cmake (found version "5.44.0")
-- Found KF5IconThemes: /usr/lib/x86_64-linux-gnu/cmake/KF5IconThemes/KF5IconThemesConfig.cmake (found version "5.44.0")
-- Found KF5ItemViews: /usr/lib/x86_64-linux-gnu/cmake/KF5ItemViews/KF5ItemViewsConfig.cmake (found version "5.44.0")
-- Found KF5Notifications: /usr/lib/x86_64-linux-gnu/cmake/KF5Notifications/KF5NotificationsConfig.cmake (found version "5.44.0")
-- Found KF5Parts: /usr/lib/x86_64-linux-gnu/cmake/KF5Parts/KF5PartsConfig.cmake (found version "5.44.0")
-- Found KF5Solid: /usr/lib/x86_64-linux-gnu/cmake/KF5Solid/KF5SolidConfig.cmake (found version "5.44.0")
-- Found KF5TextWidgets: /usr/lib/x86_64-linux-gnu/cmake/KF5TextWidgets/KF5TextWidgetsConfig.cmake (found version "5.44.0")
-- Found KF5Wallet: /usr/lib/x86_64-linux-gnu/cmake/KF5Wallet/KF5WalletConfig.cmake (found version "5.44.0")
-- Found KF5WidgetsAddons: /usr/lib/x86_64-linux-gnu/cmake/KF5WidgetsAddons/KF5WidgetsAddonsConfig.cmake (found version "5.44.0")
-- Found KF5WindowSystem: /usr/lib/x86_64-linux-gnu/cmake/KF5WindowSystem/KF5WindowSystemConfig.cmake (found version "5.44.0")
-- Found KF5XmlGui: /usr/lib/x86_64-linux-gnu/cmake/KF5XmlGui/KF5XmlGuiConfig.cmake (found version "5.44.0")
-- Found KF5GuiAddons: /usr/lib/x86_64-linux-gnu/cmake/KF5GuiAddons/KF5GuiAddonsConfig.cmake (found version "5.44.0")
-- Found KF5: success (found version "5.44.0") found components:  Archive Bookmarks Codecs Completion CoreAddons Config DocTools I18n IconThemes ItemViews KIO Notifications Parts Solid TextWidgets Wallet WidgetsAddons WindowSystem XmlGui GuiAddons
kdesu path set: /usr/lib/x86_64-linux-gnu/libexec/kf5/kdesu
-- Looking for include file attr/libattr.h
-- Looking for include file attr/libattr.h - not found
-- Looking for include file sys/xattr.h
-- Looking for include file sys/xattr.h - found
-- Looking for include file sys/acl.h
-- Looking for include file sys/acl.h - not found
-- Looking for include file acl/libacl.h
-- Looking for include file acl/libacl.h - not found
-- /home/user/krusader/krusader: skipped subdir $(KRJSDIR)
-- Found ZLIB: /usr/lib/x86_64-linux-gnu/libz.so (found version "1.2.11")
-- The following REQUIRED packages have been found:

 * ECM (required version >= 1.7.0)
 * Qt5Concurrent
 * Qt5Core
 * Qt5Gui
 * Qt5DBus
 * Qt5Widgets
 * Qt5PrintSupport
 * Qt5Xml
 * Qt5 (required version >= 5.5)
 * KF5Archive
 * KF5Bookmarks
 * KF5Codecs
 * KF5Completion
 * KF5CoreAddons
 * KF5Config
 * KF5DocTools
 * Gettext
 * PythonInterp
 * KF5I18n
 * KF5IconThemes
 * KF5ItemViews
 * KF5KIO
 * KF5Notifications
 * KF5Parts
 * KF5Solid
 * KF5TextWidgets
 * KF5Wallet
 * KF5WidgetsAddons
 * KF5WindowSystem
 * KF5XmlGui
 * KF5GuiAddons
 * KF5

-- Configuring done
-- Generating done
-- Build files have been written to: /home/user/krusader-build

```
