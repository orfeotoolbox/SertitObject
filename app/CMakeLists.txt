cmake_minimum_required (VERSION 2.8)

OTB_CREATE_APPLICATION(NAME Aggregate
                       SOURCES otbAggregate.cxx
                       LINK_LIBRARIES ${${otb-module}_LIBRARIES}
)

OTB_CREATE_APPLICATION(NAME ObjectsRadiometricStatistics
                       SOURCES otbObjectsRadiometricStatistics.cxx
                       LINK_LIBRARIES ${${otb-module}_LIBRARIES}
)
