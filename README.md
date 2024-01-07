@@ -1,8 +1,8 @@
language: python
python:
 - "3.4"
 - "3.5"
 - "3.6"
 - "3.7"
install:
 - pip install -r requirements.txt coverage coveralls
 - python download_corpora.py
  2 changes: 1 addition & 1 deletion2  
newspaper/version.py
@@ -7,5 +7,5 @@
__license__ = 'MIT'
__copyright__ = 'Copyright 2014, Lucas Ou-Yang'

version_info = (0, 2, 8)
version_info = (0, 3, 0)
__version__ = ".".join(map(str, version_info))
  2 changes: 1 addition & 1 deletion2  
requirements.txt
@@ -11,4 +11,4 @@ python-dateutil>=2.5.3
PyYAML>=3.11
requests>=2.10.0
tinysegmenter==0.3  # TODO(codelucas): Investigate making this >=0.3
tldextract>=2.0.1
tldextract>=2.0.1
  2 changes: 1 addition & 1 deletion2  
setup.py
@@ -47,7 +47,7 @@

setup(
    name='newspaper3k',
    version='0.2.8',
    version='0.3.0',
    description='Simplified python article discovery & extraction.',
    long_description=readme,
    author='Lucas Ou-Yang',
