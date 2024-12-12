# cmake-format: off
# SPDX-License-Identifier: GPL-3.0-or-later.
# Copyright © 2024 The TokTok team
# cmake-format: on

cmake_minimum_required(VERSION 3.16)
cmake_policy(VERSION 3.16)
project(qtox-resources)

find_package(Qt6Core REQUIRED)

qt_add_binary_resources(Noto smileys/Noto/emoticons.qrc)
qt_add_binary_resources(OpenMoji smileys/OpenMoji/emoticons.qrc)
