drake_add_cc_test(double_pendulum_test)
target_link_libraries(double_pendulum_test Eigen3::Eigen drakeMultibodyTree
  drakeMultibodyBenchmarks)

drake_add_cc_test(multibody_tree_indexes_test multibody_tree_indexes_test.cc)
target_link_libraries(multibody_tree_indexes_test drakeCommon)

drake_add_cc_test(multibody_tree_creation_test multibody_tree_creation_test.cc)
target_link_libraries(multibody_tree_creation_test drakeMultibodyTree)

drake_add_cc_test(rotational_inertia_test)
target_link_libraries(rotational_inertia_test Eigen3::Eigen drakeCommon)

drake_add_cc_test(spatial_inertia_test)
target_link_libraries(spatial_inertia_test Eigen3::Eigen drakeCommon)

drake_add_cc_test(unit_inertia_test)
target_link_libraries(unit_inertia_test Eigen3::Eigen drakeCommon)

