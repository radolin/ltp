# SPDX-License-Identifier: GPL-2.0-or-later
# Copyright (c) International Business Machines  Corp., 2009

top_srcdir		?= ../../../..

include $(top_srcdir)/include/mk/testcases.mk

CPPFLAGS		+= -I$(abs_srcdir)/../utils
LDLIBS			+= -lpthread -lrt

include $(top_srcdir)/include/mk/generic_leaf_target.mk
