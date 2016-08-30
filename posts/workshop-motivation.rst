.. title: Workshop Motivation
.. slug: workshop-motivation
.. date: 2016-08-30 10:52:40 UTC-04:00
.. tags:
.. category:
.. link:
.. description:
.. type: text

The purpose of this workshop is to get together "in real life" a group of
scientists and software developers who have, until now, mostly been interacting
online. Our group started on the `xarray mailing list <https://groups.google.com/d/msgid/xarray/2c3554f8-8b79-4bd5-b77a-b1b693f2e0da%40googlegroups.com.>`__
and then moved to a `hackpad <https://aospy.hackpad.com>`__.

The motivation of this workshop, and the group in general, is to build a toolkit
for the analysis of ocean and atmosphere general circulation model (GCM) output
based on `xarray <https://xarray.pydata.org>`__ and
`dask <http://dask.pydata.org>`__.

Quoting from the `summary hackpad <https://aospy.hackpad.com/Summary-of-1st-brainstorming-round-lLJ3vXhCk7Z>`__,

  Problem: Each group builds on their own (in some cases proprietary)
  infrastructure: NCAR has PyNIO; PCMDI has UV-CDAT; UKMO has Iris. Ideal:
  single "standard" toolkit for analysis, i.e. create for climate-related
  sciences what astropy is for astronomy-related sciences.

  None of the existing platforms utilize xarray and its amazing netCDF-like
  named dimensions and coordinates.  Given their age, it's safe to assume also
  that none of the aforementioned packages are built from the core (no pun
  intended) to support out-of-core computations.  xarray provides the
  opportunity to do so through dask.  Moreover, through dask-distributed, this
  has the potential of extending straightforwardly from single nodes to across
  nodes, thereby harnessing the full power of large computational clusters that
  many climate researchers have access to.

  It is our determination that xarray and out-of-core are the future of climate-
  related computation using Python, and conversely that Python is the future of
  climate-related computation.  This puts us in a unique position to introduce a
  set of tools that becomes the community standard and greatly enhances the
  speed and reliability of such computations and therefore of the science
  itself.
