Changelog
=========

4.1.2 (2025-11-21)
------------------
- Change: Defaults to Plone 6.1 and Python 3.12
  [avoinea]

4.1.1 (2025-11-21)
------------------
- Bugfix: Remove python requirements from setup.py
  [avoinea]

4.1.0 (2025-11-21)
------------------
- Change: Upgrade to Plone 6.1.3
  [avoinea]
- Change: Remove buildout, tox and travis files
  [avoinea]
- Change: Update classifiers in setup.py
  [avoinea]
- Change: Update Jenkinsfile to use ruff for linting and run tests in Python 3 / Plone 6
  [avoinea]

4.0.8 (2021-11-11)
------------------
- Change: Upgrade to Plone 6
  [avoinea]

4.0.7 (2021-04-14)
------------------
- Bugfix: Fix Jenkinsfile and long_description_content_type
  [avoinea]

4.0.6 (2021-04-03)
------------------
- Change: Disable WWW and KGS tests in Jenkinsfile by default to be able to release the egg
  [avoinea]
- Bugfix: Fix Jenkinsfile python3 Docker container name
  [avoinea]

4.0.5 (2020-12-03)
------------------
- Change: Modified addon template so that you can now create packages with 2
  namespaces e.g. eea.foo.bar
  [iulianpetchesi]

4.0.5rc5 (2020-11-25)
---------------------
- Cleanup: Fix pylint, pep8
  [avoinea]

4.0.5rc4 (2020-11-25)
---------------------
- Cleanup: Remove CasperJS functional tests
  [avoinea]

4.0.5rc3 (2020-09-02)
---------------------
- Cleanup: Update Jenkinsfile and setup.py
  [avoinea]

4.0.5rc2 (2019-05-09)
---------------------
- Bug fix: Fix addon setup.py.bob syntax
  [avoinea]

4.0.5.rc1 (2019-05-09)
----------------------

- Initial release based on bobtemplates.plone 4.0.5
  [avoinea]
