
# Internal Notes

To build:
 - Update version in setup.py
 - run `python3 setup.py sdist bdist_wheel`
 - run `twine upload dist/*`
 - delete build folder when done
 - Delete older "dist" versions (keep latest two is ok)
 - Update to Github (git add ., git commit -m "test", git push)

See references here: https://packaging.python.org/tutorials/packaging-projects/
