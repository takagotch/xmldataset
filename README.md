### xmldataset
---
https://github.com/spurin/xmldataset/

https://xmldataset.readthedocs.io/en/latest/

```py
// tests/test_xmldataset.py

try:
  import unittest2 as unittest
except ImportError:
  import unittest
  
from xmldataset import parse_using_profile

class TestImports(unittest.TestCase):
  
  def test_import_parse_using_profile(self):
    try:
      from xmldataset import parse_using_profile
      pass
    except:
      raise Exception('Failed to import parse_using_profile')
  
  def test_dict_equal(self):
    self.assertDictEqual({'name': 'james'}, {'name' : 'james'})


```

```
```

```
```


