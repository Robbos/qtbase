# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: BSD-3-Clause

# Generated from time.pro.

add_subdirectory(qcalendar)
add_subdirectory(qdate)
add_subdirectory(qdatetime)
add_subdirectory(qdatetimeparser)
add_subdirectory(qtime)
if(QT_FEATURE_timezone AND NOT INTEGRITY)
    add_subdirectory(qtimezone)
endif()
