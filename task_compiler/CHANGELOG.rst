^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package task_compiler
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.3 (2015-01-31)
------------------
* remove rosbuild stuff, change to pure catkin packages
* remove rosbuild stuff, change to pure catkin packages
* also removed from build_depend
* pddl_planner and roseus_smach is not used in cmake
* add option result success and fail
* support failure plan
* add planner option for downward
* Contributors: Yuki Furuta, Kei Okada

0.1.2 (2014-05-06)
------------------

0.1.1 (2014-05-05)
------------------
* catkinize jsk_planning
* add argument for debug
* fix minor bug
* update depend on roseus_smach
* forgot to add romeo_action.l
* added sample programs for romeo
* removed pr2eus_openrave dependency
* fixed pr2eus_openrave method name
* remove mismatched parentheses
* object in ADL typing may be keyword, should not use??
* dump generated state machine to /tmp/action_state_machine.l for reuse
* add room cleaning sample of task_compiler
* remove empty file
* add scripts for room cleaning planning sample, but it will work tomorrow
* change debug print
* fix smach_structure publish properly timing, add user input action to task_compiler
* add level 0 example and fix bug in launch syntax
* add new package task_compiler, which is a converter from PDDL description to SMACH executable graph.
* Contributors: Kei Okada, Manabu Saito, Hiroyuki Mikita, Youhei Kakiuchi
