#
# Copyright (C) 2009 Ziyan Zhou <zhou@ziyan.info>
# Visit http://ziyan.info/tag/head-tracking/ for more information
#
# This file is part of Head Tracking Display.
#
# Head Tracking Display is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# Head Tracking Display is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with Head Tracking Display.  If not, see <http://www.gnu.org/licenses/>.
#

libdir = $(prefix)/share/player/plugins/
lib_LTLIBRARIES = libface.la

AM_CPPFLAGS = -Wall -g -ggdb
AM_CPPFLAGS += $(PLAYERCORE_CFLAGS)
AM_CPPFLAGS += $(OPENCV_CFLAGS)

libface_la_SOURCES = face.cc ../common/camera.cc
libface_la_LDFLAGS = $(PLAYERCORE_LIBS) $(OPENCV_LIBS)
