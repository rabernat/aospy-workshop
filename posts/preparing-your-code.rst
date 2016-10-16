.. title: Preparing your Code
.. slug: preparing-your-code
.. date: 2016-10-15 21:25:31 UTC-04:00
.. tags:
.. category:
.. link:
.. description:
.. type: text

In order to make the most out of our workshop, participants are encouraged to
polish their code as much as possible beforehand. Through our discussions on
Saturday, we will try to select one or more projects as the target of a coding
sprint on Sunday. To enable others to effectively contribute to your project,
try to follow best practices for open source software development. Below is a
list of recommended practices for participating projects:

- Hosting on `GitHub <http://github.org>`_ to facilitate issues tracking, pull
  requests, etc.
- Comprehensive test suite. Matt Rocklin's
  `blog post on testing <http://matthewrocklin.com/blog/work/2016/02/08/tests>`_
  clearly explains the importance of testing to a scientific software project.
  Without tests, it is effectively impossible for others (or even you) to
  make significant contributions to your code.
- Continuous integration of testing via an online service such as
  `Travis CI <https://travis-ci.org/>`_ or `circleci <https://circleci.com/>`_.
  The use of continuous integration really facilitates collaboration, making
  it clear when pull requests break existing functionality.
- `Code coverage <http://docs.codecov.io/docs/about-code-coverage#section-what-is-code-coverage>`_
  assesment. Coverage tells you which parts of your code are covered by your
  test suite. Coverage can be integrated with GitHub via services such as
  `Coveralls <https://coveralls.io/>`_ and `Codecov <https://codecov.io/>`_.
- Comprehensive documentation. Many modern python packages use
  `Sphinx <www.sphinx-doc.org>`_ for the documentation, which integrates with
  http://readthedocs.org/ via GitHub_ hooks.
- Clear specification of dependencies. It's safe to assume that everyone will
  be using Anaconda for package management, so an
  `environment.yml file <http://conda.pydata.org/docs/using/envs.html>`_ is
  sufficient to specify your project's dependencies.

In addition to these general best practices, there are some specific issues
related to analysis of GCM data. Most of us are aiming for somewhat
universal tools (i.e. tools compatible with many different models), but in
practice, we usually have a specific model we focus on and use for testing
our code. Therefore, participants are highly encouraged to make some sample
output from their favorite model (i.e. CAM, NEMO, MITgcm, etc.) available
online in a publicly accessible location. These links will be shared with the
group. If you don't have the ability to post sample data online, you can
upload it to the `LDEO anonymous incoming FTP server
<http://www.ldeo.columbia.edu/campus-services/ldeo-it/file-transfer-ftp>`_ in
the "aospy" directory.
