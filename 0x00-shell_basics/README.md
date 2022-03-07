# For magic file task
- First create a school file using: 
```
  vi school
```
- Then enter content into file:
```
  0 string SCHOOL School data
  !:mime School
```
- compile school file using: 
```
  file -C -m school
```
- test file using: 
```
  file --mime-type -m school.mgc *
```
