TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += pugixml
INC += pugixml.hpp

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install pugixml.dbd into <top>/dbd
#DBD += pugixml.dbd

# specify all source files to be compiled and added to the library
pugixml_SRCS += pugixml.cpp

pugixml_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

