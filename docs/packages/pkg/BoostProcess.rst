.. spelling::

    BoostProcess

.. index:: frameworks ; BoostProcess

.. _pkg.BoostProcess:

BoostProcess
============

-  `Official <https://github.com/BorisSchaeling/boost-process>`__
-  `Hunterized <https://github.com/alamaison/boost-process/tree/cmake>`__
-  `Example <https://github.com/ruslo/hunter/blob/develop/examples/Boost-process/CMakeLists.txt>`__
-  Added by `Alexander Lamaison <https://github.com/alamaison>`__
   (`pr-330 <https://github.com/ruslo/hunter/pull/330>`__)
-  Available since
   `v0.12.50 <https://github.com/ruslo/hunter/releases/tag/v0.12.50>`__

.. code-block:: cmake

    hunter_add_package(BoostProcess)
    find_package(BoostProcess CONFIG REQUIRED)
    target_link_libraries(... BoostProcess::boost_process)
