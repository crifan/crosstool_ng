# Author: crifan
# Date: 2012-05-16
#
# -----------------------------------------------------------------
#  generate output from DocBook sources
#  this is entry makefile for docbook
# -----------------------------------------------------------------
# run this makefile under src directory:
# [office]
# pwd = /home/CLi/develop/docbook/books/xxx/src
# [home]
# pwd = /cygdrive/e/Dev_Root/docbook/dev/books/xxx/src

################################################################################
# Project Settings
################################################################################

# also means main source file name
PROJECT_NAME = crosstool_ng
SUB_SRC_FILES = \
    preface.xml \
    ch01_crosstool_ng_intro.xml \
    ch02_download_install_crosstool_ng.xml \
    ch03_config_crosstool_ng.xml \
    ch04_build_crosstool_ng.xml \
    ch05_crosstool_ng_common_errors.xml \
    ch06_crosstool_ng_related.xml \
    reference.xml \

DOCBOOK_MAKEFILE_ROOT = ../../../config
################################################################################
# Include docbook makefile
################################################################################
include $(DOCBOOK_MAKEFILE_ROOT)/docbook.mk