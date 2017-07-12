cmake_minimum_required (VERSION 2.8)

OTB_CREATE_APPLICATION(NAME Aggregate
                       SOURCES otbAggregate.cpp
                       LINK_LIBRARIES ${${otb-module}_LIBRARIES}
)

OTB_CREATE_APPLICATION(NAME ObjectsRadiometricStatistics
                       SOURCES otbObjectsRadiometricStatistics.cpp
                       LINK_LIBRARIES ${${otb-module}_LIBRARIES}
)
