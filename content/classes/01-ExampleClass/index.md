# Example Class page

This is an example of a class page, the way we sugest to organize the course material is:

- Each class is a folder in `classes`
    - We suggest to enumarate the class (`ie: 01-example`)
- The class folder will hold:
    - `index.md`: (this file) A markdown file with the class material
    - Images, presentantion and extra material for the specific class
    - `slides.pdf`
    
To create a new class, first create the folder and its materials, than edit the `mkdocs.yml` adding the path to the `index.md`.

```diff
nav:
  - Home: index.md
  - Classes:
+    - classes/01-ExampleClass/index.md
```

!!! tip
    If this class has slides, name it as `slides.pdf` and it will be automatic show on the top of the page. 
    
    - https://insper-education.github.io/active-handout/reference/slides/
