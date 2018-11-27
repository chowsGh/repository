## 保存一些安装包

- 开发工具(win,linux)

- 分割-合并工具${reopsitory}/tool/atom.util-0.0.1-SNAPSHOT.one-jar.jar

  ```java
  if ("split".equals(action)) {
              String filePath = args[1];// "H:\\CLYDE_REPOSITORY\\qrepository\\win\\develop\\mongo\\mongodb-compass-community-1.15.4-win32-x64.zip";
              String targetPath = args[2];// "H:\\CLYDE_REPOSITORY\\qrepository\\win\\develop\\mongo\\"
              split(filePath, targetPath);
          } else {
              String sourceFilePath = args[1];// "H:\\CLYDE_REPOSITORY\\qrepository\\win\\develop\\mongo\\";
              String sourceFileName = args[2];// "mongodb-compass-community-1.15.4-win32-x64";
              String targetFileName = args[3];// "compose_mongodb-compass-community-1.15.4-win32-x64.zip";
              String targetPath = args[4];// "H:\\CLYDE_REPOSITORY\\qrepository\\win\\develop";
              compose(sourceFilePath, sourceFileName, targetFileName, targetPath);
          }
  ```


