cmake_minimum_required(VERSION 3.6.0)

add_library(hello_jni SHARED
            hello_jni.c)

#target_link_libraries(hello_jni
##        android
##        log)