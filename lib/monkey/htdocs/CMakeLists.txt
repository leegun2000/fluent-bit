if(NOT BUILD_LOCAL)
  set(SRC ${PROJECT_SOURCE_DIR}/htdocs/)
  install(DIRECTORY ${SRC} DESTINATION ${MK_PATH_WWW})
endif()
