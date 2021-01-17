neurotic-constructor
====================

|Windows badge| |macOS badge| |Linux badge|

A `conda constructor`_ recipe for the *neurotic* package.

Related repositories:

- `neurotic`_
- `neurotic-feedstock`_

Automated Builds
----------------

When new commits are pushed to this repository, `GitHub Actions`_ will
automatically build standalone installers for Windows, macOS, and Linux. They
can then be downloaded from `GitHub Actions`_.

Building Manually
-----------------

Install conda constructor if necessary::

    conda install constructor

Change directories and run constructor::

    cd neurotic-constructor
    constructor


.. |Linux badge| image:: https://github.com/jpgill86/neurotic-constructor/workflows/Linux%20installer/badge.svg
    :target: https://github.com/jpgill86/neurotic-constructor/actions?query=workflow%3A%22Linux+installer%22
    :alt: Linux installer

.. |macOS badge| image:: https://github.com/jpgill86/neurotic-constructor/workflows/macOS%20installer/badge.svg
    :target: https://github.com/jpgill86/neurotic-constructor/actions?query=workflow%3A%22macOS+installer%22
    :alt: macOS installer

.. |Windows badge| image:: https://github.com/jpgill86/neurotic-constructor/workflows/Windows%20installer/badge.svg
    :target: https://github.com/jpgill86/neurotic-constructor/actions?query=workflow%3A%22Windows+installer%22
    :alt: Windows installer

.. _conda constructor:  https://github.com/conda/constructor
.. _GitHub Actions:     https://github.com/jpgill86/neurotic-constructor/actions
.. _neurotic:           https://github.com/jpgill86/neurotic
.. _neurotic-feedstock: https://github.com/conda-forge/neurotic-feedstock
