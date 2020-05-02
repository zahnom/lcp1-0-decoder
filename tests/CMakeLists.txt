add_executable(GoogleTestsRun main.cpp lcp1-0-decoderTests.cpp)

include_directories(${PROJECT_SOURCE_DIR}/src)
include_directories(${googletest_SOURCE_DIR}/include ${googletest_SOURCE_DIR})

target_link_libraries(GoogleTestsRun lcp1-0-decoder gtest gtest_main)