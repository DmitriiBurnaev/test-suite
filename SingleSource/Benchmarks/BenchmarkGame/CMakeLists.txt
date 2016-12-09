if(NOT ARCH STREQUAL "ARC")
    add_subdirectory(Large)
endif()    

list(APPEND LDFLAGS -lm)
llvm_singlesource()
