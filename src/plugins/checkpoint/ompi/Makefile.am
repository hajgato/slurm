# Makefile for checkpoint/ompi plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

AM_CPPFLAGS = -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = checkpoint_ompi.la

# OpenMPI checkpoint plugin.
checkpoint_ompi_la_SOURCES = checkpoint_ompi.c
checkpoint_ompi_la_LDFLAGS = $(PLUGIN_FLAGS)
