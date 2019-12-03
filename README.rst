.. image:: https://img.shields.io/badge/testn--085-lsst.io-brightgreen.svg
   :target: https://testn-085.lsst.io
.. image:: https://travis-ci.com/lsst-sqre-testing/testn-085.svg
   :target: https://travis-ci.com/lsst-sqre-testing/testn-085
..
  Uncomment this section and modify the DOI strings to include a Zenodo DOI badge in the README
  .. image:: https://zenodo.org/badge/doi/10.5281/zenodo.#####.svg
     :target: http://dx.doi.org/10.5281/zenodo.#####

##########################################
Test technote from sqrbot-jr on Roundtable
##########################################

TESTN-085
=========

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin facilisis pharetra neque, at semper nulla mattis auctor. Proin semper mollis enim eget interdum. Mauris eleifend eget diam vitae bibendum. Praesent ut aliquet odio, sodales imperdiet nisi. Nam interdum imperdiet tortor sed fringilla. Maecenas efficitur mi sodales nulla commodo rutrum. Ut ornare diam quam, sed commodo turpis aliquam et. In nec enim consequat, suscipit tortor sit amet, luctus ante. Integer dictum augue diam, non pulvinar massa euismod in. Morbi viverra condimentum auctor. Nullam et metus mauris. Cras risus ex, porta sit amet nibh et, dapibus auctor leo.

**Links:**

- Publication URL: https://testn-085.lsst.io
- Alternative editions: https://testn-085.lsst.io/v
- GitHub repository: https://github.com/lsst-sqre-testing/testn-085
- Build system: https://travis-ci.com/lsst-sqre-testing/testn-085


Build this technical note
=========================

You can clone this repository and build the technote locally with `Sphinx`_:

.. code-block:: bash

   git clone https://github.com/lsst-sqre-testing/testn-085
   cd testn-085
   pip install -r requirements.txt
   make html

.. note::

   In a Conda_ environment, ``pip install -r requirements.txt`` doesn't work as expected.
   Instead, ``pip`` install the packages listed in ``requirements.txt`` individually.

The built technote is located at ``_build/html/index.html``.

Editing this technical note
===========================

You can edit the ``index.rst`` file, which is a reStructuredText document.
The `DM reStructuredText Style Guide`_ is a good resource for how we write reStructuredText.

Remember that images and other types of assets should be stored in the ``_static/`` directory of this repository.
See ``_static/README.rst`` for more information.

The published technote at https://testn-085.lsst.io will be automatically rebuilt whenever you push your changes to the ``master`` branch on `GitHub <https://github.com/lsst-sqre-testing/testn-085>`_.

Updating metadata
=================

This technote's metadata is maintained in ``metadata.yaml``.
In this metadata you can edit the technote's title, authors, publication date, etc..
``metadata.yaml`` is self-documenting with inline comments.

Using the bibliographies
========================

The bibliography files in ``lsstbib/`` are copies from `lsst-texmf`_.
You can update them to the current `lsst-texmf`_ versions with::

   make refresh-bib

Add new bibliography items to the ``local.bib`` file in the root directory (and later add them to `lsst-texmf`_).

.. _Sphinx: http://sphinx-doc.org
.. _DM reStructuredText Style Guide: https://developer.lsst.io/restructuredtext/style.html
.. _this repo: ./index.rst
.. _Conda: http://conda.pydata.org/docs/
.. _lsst-texmf: https://lsst-texmf.lsst.io
