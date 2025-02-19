^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ros2controlcli
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.1 (2021-05-31)
------------------
* Use correct names after changing arguments (`#425 <https://github.com/ros-controls/ros2_control/issues/425>`_)
  In `#412 <https://github.com/ros-controls/ros2_control/issues/412>`_ we forgot to update the argument after changing flags.
* Contributors: Denis Štogl

0.6.0 (2021-05-23)
------------------
* Renaming ros2controlcli verbs (`#412 <https://github.com/ros-controls/ros2_control/issues/412>`_)
  * Renamed verbs to match services
  * README.rst redirects to docs/index.rst
  * argument {start/stop}_controllers -> {start/stop}
  * rst include did not work, try relative link
  * Moved configure_controller doc to deprecated
  * set_state -> set-state
* Contributors: Mathias Hauan Arbo, Denis Štogl

0.5.0 (2021-05-03)
------------------
* correct return values in CLI (`#401 <https://github.com/ros-controls/ros2_control/issues/401>`_)
* [python] Update files in ros2controlcli to use format strings (`#358 <https://github.com/ros-controls/ros2_control/issues/358>`_)
* Add starting doc for ros2controlcli (`#377 <https://github.com/ros-controls/ros2_control/issues/377>`_)
* Contributors: Bence Magyar, Karsten Knese, NovusEdge

0.4.0 (2021-04-07)
------------------
* Remodel ros2controlcli, refactor spawner/unspawner and fix test (`#349 <https://github.com/ros-controls/ros2_control/issues/349>`_)
* Contributors: Karsten Knese

0.3.0 (2021-03-21)
------------------

0.2.1 (2021-03-02)
------------------

0.2.0 (2021-02-26)
------------------
* Increase service call timeout, often services take longer than 0.2s (`#324 <https://github.com/ros-controls/ros2_control/issues/324>`_)
* Contributors: Victor Lopez

0.1.6 (2021-02-05)
------------------

0.1.5 (2021-02-04)
------------------

0.1.4 (2021-02-03)
------------------
* Print error messages if ros2controlcli commands fail (`#309 <https://github.com/ros-controls/ros2_control/issues/309>`_)
* Inverse the response of cli commands to return correct exit-status. (`#308 <https://github.com/ros-controls/ros2_control/issues/308>`_)
  * Inverse the response of cli commands to return correct exit-status.
  * list verbs return exit-status 0
* Contributors: Shota Aoki, Victor Lopez

0.1.3 (2021-01-21)
------------------

0.1.2 (2021-01-06)
------------------

0.1.1 (2020-12-23)
------------------

0.1.0 (2020-12-22)
------------------
* Add configure controller service (`#272 <https://github.com/ros-controls/ros2_control/issues/272>`_)
* Use resource manager (`#236 <https://github.com/ros-controls/ros2_control/issues/236>`_)
* Add cli interface (`#176 <https://github.com/ros-controls/ros2_control/issues/176>`_)
* Contributors: Bence Magyar, Denis Štogl, Karsten Knese, Victor Lopez
