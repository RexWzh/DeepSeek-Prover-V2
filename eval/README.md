
```python
import pandas as pd
df = pd.read_json('minif2f-ds.jsonl', lines=True)

df.head()
#                                            full_name                                               code split                                   axioms  valid_4_9  valid_4_19
# 0                             mathd_numbertheory_435  import Mathlib\nimport Aesop\n\nset_option max...  test  [propext, Quot.sound, Classical.choice]       True        True
# 1                                  mathd_algebra_346  import Mathlib\nimport Aesop\n\nset_option max...  test  [propext, Classical.choice, Quot.sound]       True        True
# 2                             mathd_numbertheory_552  import Mathlib\nimport Aesop\n\nset_option max...  test  [propext, Quot.sound, Classical.choice]       True        True
# 3                                       aime_1994_p3  import Mathlib\nimport Aesop\n\nset_option max...  test  [propext, Quot.sound, Classical.choice]       True        True
# 4  algebra_apbpceq2_abpbcpcaeq1_aleq1on3anbleq1an...  import Mathlib\nimport Aesop\n\nset_option max...  test  [propext, Classical.choice, Quot.sound]       True        True
```