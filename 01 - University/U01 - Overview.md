# 1C
```dataview
LIST WITHOUT ID "[[" + file.path + "|" + aliases[0] + "]]"
FROM "01 - University/U02 - Subjects"
WHERE contains(tags, "OVERVIEW") AND contains(tags, "1C")
```
# 2C
```dataview
LIST WITHOUT ID "[[" + file.path + "|" + aliases[0] + "]]"
FROM "01 - University/U02 - Subjects"
WHERE contains(tags, "OVERVIEW") AND contains(tags, "2C")
```
---
---

# [[Profesores]]

```dataview
TABLE WITHOUT ID aliases[0] as "Materia", profesor as "Profesor/es"
FROM "01 - University/U02 - Subjects"
WHERE profesor AND aliases
```




[[SD - Overview]]
[[IO - Overview]]
[[LAB4 - Overview]]
[[TG - Overview]]
[[ALG - Overview]]
[[MIC - Overview]]
[[PPS - Overview]]
[[ELECTRO - Overview]]
[[DIRPROY - Overview]]

---
#OVERVIEW