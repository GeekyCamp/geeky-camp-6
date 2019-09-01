# Java OOP

## 1. In-memory file system

**Краен срок:** 03.09.2019, 23:59

### Условие

Design and implement a library for in-memory file system.
Memory limits and thread safety may be ignored.
The file system may contain two types of objects: files and directories.
The library has a single root directory.
Each directory may contain subdirectories and files.
Each file contains some data: characters of a certain count (i.e. only text files).
A subdirectory or a file within a directory is identified by its name.
An object within the file system is identified by its absolute path (the path of the parent directory + the object’s name). Relative paths (related to a given directory) are optional.
Files can be opened in read-write or read-only mode. An open file can be read from or written to. Open files can be closed after reading and writing is done. A single file cannot be opened again if still opened.
An object can be created within a directory. An object can be deleted from its parent directory. An object can be renamed within its parent directory. A directory cannot be deleted if not empty. An open file cannot be deleted.

Example usage scenarios:
1. Create a file within a subdirectory. Write some data in it. Close it. Open it again and read the data.
2. Open a file in read-only mode. Write some data in it. Read some data from it. Close it.
3. Delete a file and then open it.
4. Delete recursively a non-empty directory.
5. Create/open/delete a file using its absolute path.
6. Create a subdirectory within a directory with a given name. Create a file within the same directory with the same name.

### Оценяване

Функционална коректност носи 0-5 точки, ОО дизайнът се оценява с 0-5 точки, изборът на подходящи структури от данни - 0-3, чистият код - 0-3 точки. Допълнителни 2 точки получават първите трима, предали функционално пълно решение и ще по 1 точка за вторите трима.

> **Забележка:** Домашни, предадени след крайния срок, се приемат и оценяват, но се отнемат 2 точки от оценката.
