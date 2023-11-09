# git-tutorial
[¯\_(ツ)_/¯](https://ohshitgit.com/ru)

### Показать рабочую директорию (Present / Print Working Directory)
```
pwd
```
### Создать папку
```
mkdir dir1
```
### Просмотр содержимого папки
```
ls
```
```
ls -a
```
```
ls -al
```
### Удалить папку
```
rmdir dir1
```
### Создать папку с содержимым
```
mkdir -p dir1/dir/2/dir3
```
### Удалить папку с содержимым
```
rm -r dir1
```
### Создать пустой файл
```
touch file.txt
```
### Создать / Перезаписать файл с содержимым
```
echo '123' > file.txt
```
### Создать / Дописать файл с содержимым
```
echo '345' >> file.txt
```
### Просмотр файла
```
cat file.txt
```
### Удалить файл
```
rm file.txt
```
### Копировать файл
```
cp file.txt dir1
```
### Переместить файл
```
mv file.txt dir1
```
```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 
