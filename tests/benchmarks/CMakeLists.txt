# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: BSD-3-Clause

# Generated from benchmarks.pro.

add_subdirectory(corelib)
add_subdirectory(sql)
if(TARGET Qt::DBus)
    add_subdirectory(dbus)
endif()
if(TARGET Qt::Gui)
    add_subdirectory(gui)
endif()
if(TARGET Qt::Network)
    add_subdirectory(network)
endif()
if(TARGET Qt::Test)
    add_subdirectory(testlib)
endif()
if(TARGET Qt::Widgets)
    add_subdirectory(widgets)
endif()
