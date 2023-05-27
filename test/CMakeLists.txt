find_package(Catch2 CONFIG REQUIRED)

add_executable(test tests.cpp)

target_link_libraries(test PRIVATE Catch2::Catch2 Catch2::Catch2WithMain)