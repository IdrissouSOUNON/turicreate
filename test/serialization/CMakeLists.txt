project(Turi)

make_boost_test(serializetests.cxx REQUIRES unity_shared_for_testing)
make_boost_test(eigen_serialization.cxx REQUIRES unity_shared_for_testing)
