set(the_description "Object detection algorithms")

if (BUILD_opencv_apps AND NOT (APPLE_FRAMEWORK OR WINRT OR IOS))    
  add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/tools) 
endif()
