### Simple format for cfdirectory

### Directory Create
```lucee
<cfdirectory action="create" directory="path of directory">
```

### Directory List
```lucee
<cfdirectory action="list" directory="path of directory" name="list" type="file" listinfo="name">
```
### Directory Copy
```lucee
<cfdirectory action="copy" directory="path of directory" destination="path of destination" nameconflict="Overwrite" recurse="true">

```
### Directory Rename
```lucee
<cfdirectory action="rename" directory="path of directory" newDirectory="rename of directory">

```
### Directory Delete
```lucee
<cfdirectory action="Delete" directory="path of directory">
```
### Directory Forcedelete
```lucee
<cfdirectory action="forcedelete" directory="path of directory">
```