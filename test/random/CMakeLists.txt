project(Turi)
#make_boost_test(random_test.cxx REQUIRES unity_shared_for_testing)
make_executable(alias_benchmark SOURCES test_alias.cpp REQUIRES unity_shared_for_testing)
