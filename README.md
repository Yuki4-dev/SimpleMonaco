# SimpleMonaco
WPFで動作するシンプルなMonacoEditorです。
コマンドライン引数を指定することで、開くファイルと言語シンタックスを選択することができます。
Ctrl＋Sで名前を付けて保存or上書き保存を行うことができます。

# DEMO
![image](https://user-images.githubusercontent.com/54029057/163654918-57e2ea5d-13b9-47aa-bce0-32c6953c31b8.png)

# Usage
- コマンドライン引数なし
```
SimpleMonaco.exe
```
- コマンドライン引数（ファイル指定）
```
SimpleMonaco.exe C:\Users\Desktop\Sample.js
```
- コマンドライン引数（ファイル指定＋言語指定）
```
SimpleMonaco.exe C:\Users\Desktop\Sample.js javascript 
```

# Note
- Monaco Editor

https://microsoft.github.io/monaco-editor/

- Monaco Editorとインストールと更新
```
npm install monaco-editor@{VERSION}
```
以下のディレクトリにインストールした「monaco-editor」を配置する。
```
/SimpleMonaco/html/node_modules/
```
