^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gz_plugin_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.1 (2025-10-01)
------------------
* Merge pull request `#10 <https://github.com/gazebo-release/gz_plugin_vendor/issues/10>`_ from gazebo-release/releasepy/rolling/4.0.0
  Bump version to 4.0.0
* Bump version to 4.0.0
* Add dsv for PYTHONPATH for Jetty packages (`#9 <https://github.com/gazebo-release/gz_plugin_vendor/issues/9>`_)
  * Set PYTHONPATH for unversioned packages
  * Set PYTHONPATH from separate dsv file
  ---------
* Contributors: Addisu Z. Taddese, Jose Luis Rivero, Steve Peters

0.3.0 (2025-09-08)
------------------
* Jetty support: 4.0.0-pre1 (`#7 <https://github.com/gazebo-release/gz_plugin_vendor/issues/7>`_)
* Contributors: Steve Peters

0.2.2 (2025-05-23)
------------------
* Bump version to 3.1.0 (`#6 <https://github.com/gazebo-release/gz_plugin_vendor/issues/6>`_)
* Contributors: Ian Chen, Jose Luis Rivero

0.2.1 (2025-02-19)
------------------
* Bump version to 3.0.1 (`#5 <https://github.com/gazebo-release/gz_plugin_vendor/issues/5>`_)
* Contributors: Carlos Agüero

0.2.0 (2024-09-30)
------------------
* Bump version to 3.0.0 (`#3 <https://github.com/gazebo-release/gz_plugin_vendor/issues/3>`_)
* Apply prerelease suffix (`#2 <https://github.com/gazebo-release/gz_plugin_vendor/issues/2>`_)
  * Apply prerelease suffix
  * Drop BUILD_DOCS
  ---------
* Upgrade to Ionic
* Contributors: Addisu Z. Taddese

0.1.0 (2024-04-23)
------------------
* Use an alias target for root library
* Contributors: Addisu Z. Taddese

0.0.3 (2024-04-10)
------------------
* Add support for the `<pkg>::<pkg>` and `<pkg>::all` targets, fix sourcing of dsv files
* Contributors: Addisu Z. Taddese

0.0.2 (2024-04-08)
------------------
* Update vendored version to 2.0.3
* Fix sourcing of .dsv file
* Require calling `find_package` on the underlying package
* Fix linter (`#1 <https://github.com/gazebo-release/gz_plugin_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese
