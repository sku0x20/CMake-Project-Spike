add_executable(app app.cpp RandomIntGenerator.cpp)

target_compile_features(app PRIVATE cxx_std_17)

target_link_libraries(app PRIVATE fmt::fmt)
