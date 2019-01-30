Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the chaincashd tests manually, launch src/test/test_chaincash .

To add more chaincashd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the chaincash-qt tests manually, launch src/qt/test/chaincash-qt_test

To add more chaincash-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
