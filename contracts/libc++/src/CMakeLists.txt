add_wast_library(TARGET libc++
  SOURCE_FILES algorithm.cpp any.cpp bind.cpp condition_variable.cpp exception.cpp functional.cpp
               future.cpp ios.cpp iostream.cpp locale.cpp memory.cpp mutex.cpp new.cpp optional.cpp
               regex.cpp shared_mutex.cpp stdexcept.cpp string.cpp strstream.cpp system_error.cpp
               thread.cpp typeinfo.cpp utility.cpp valarray.cpp variant.cpp vector.cpp
  INCLUDE_FOLDERS "${STANDARD_INCLUDE_FOLDERS}"
  DESTINATION_FOLDER ${CMAKE_CURRENT_BINARY_DIR}
)
