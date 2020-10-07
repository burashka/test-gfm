# test-gfm
Проект для тестирования синтаксиса GFM

1            | 2 | 3 | 4
:--- | :--- | :--- | :---
Путь в Аркадии | `x/y/a.py` | `x/y/z/b.py` | `x/y/__init__.py`
Default | `import x.y.a` | `import x.y.z.b` | `import x.y`
`TOP_LEVEL` | `import a` | `import a.b` | **запрещено**
`NAMEPASE n.s` | `import n.s.a` | `import n.s.a.b` | `import n.s`
