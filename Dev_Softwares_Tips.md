# Dev Softwares Tips

## 01. VS Code (Windows)

### 1. Shortcuts

#### 1.1 HTML

##### 1.1.1 Comment code

<kbd>Ctrl</kbd> + <kbd>:</kbd>    

##### 1.1.2 Format document

<kbd>Shift</kbd> + <kbd>Alt</kbd>+ <kbd>F</kbd>        

##### 1.1.3 Copy line or block selection under selection

<kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Down</kbd>

<kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Up</kbd>

##### 1.1.4 Multiple selections (multi-cursor)

###### 1.1.4.1 Secondary cursors

<kbd>Alt</kbd> + <kbd>Click</kbd> 

###### 1.1.4.2 More cursors

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Down</kbd>

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Up</kbd>

### 2. VS Code Extensions

#### 2.1 Markdown Preview Enhanced

##### 2.1.1 In order to run chunks, you must enable script execution !

> ⚠️ **Script execution is off by default and needs to be explicitly enabled in Atom package / VSCode extension preferences**
>
> Please use this feature with caution because it may put your security at risk!
> Your machine can get hacked if someone makes you open a markdown with malicious code while script execution is enabled.

**Option name :** `enableScriptExecution`

*Source : [https://github.com/shd101wyy/markdown-preview-enhanced/blob/master/docs/code-chunk.md](https://github.com/shd101wyy/markdown-preview-enhanced/blob/master/docs/code-chunk.md)*

##### 2.1.2 In order to run PHP chunks, you must have defined the  PHP path for the variable "Path" in Windows User Environment Variables !

## 02. XAMPP (Windows)

### 1. Move the document root (`htdocs`)

1. Open `C:\xampp\apache\conf\httpd.conf`
2. Modify the path here :
    ```
    DocumentRoot "C:/xampp/htdocs"
    <Directory "C:/xampp/htdocs">
    ```
3. Copy `htdocs` folder content to the new location

### 2. Move the databases (`datadir`) 

1. Open `C:\xampp\mysql\bin\my.ini`
2. Modify the path here :
    ```
   datadir="C:/xampp/mysql/data"
    ```
3. Copy `data` folder content to the new location
