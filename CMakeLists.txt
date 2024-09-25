add_library(mapbox-jni.hpp INTERFACE)
add_library(mapbox::jni.hpp ALIAS mapbox-jni.hpp)
target_include_directories(mapbox-jni.hpp INTERFACE include)
