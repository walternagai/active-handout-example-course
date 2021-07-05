# Example Lab page

This is an example of a lab page, the way we sugest to organize the course material is:

- Each lab is a folder in `labs`
    - We suggest to enumarate the lab (`ie: 01-ExampleLab`)
- The class folder will hold:
    - `index.md`: (this file) A markdown file with the class material
    - Images, presentantion and extra material for the specific class
    
To create a new lab, first create the folder and its materials, than edit the `mkdocs.yml` adding the path to the `index.md`.

```diff
nav:
  - Home: index.md
  - Classes:
    - classes/01-ExampleClass/index.md
  - Laboratories:
+    - labs/01-ExampleLab/index.md
```
