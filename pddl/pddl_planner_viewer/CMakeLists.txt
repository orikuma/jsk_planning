cmake_minimum_required(VERSION 2.8.3)
project(pddl_planner_viewer)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
    DEPENDS pddl_msgs #
    CATKIN_DEPENDS # TODO
    INCLUDE_DIRS # TODO include
    LIBRARIES # TODO
)

install(DIRECTORY sample src
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
        USE_SOURCE_PERMISSIONS)


