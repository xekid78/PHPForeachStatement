# PHPForeachStatement
foreach文

## 処理
配列の内容をforeach文を使って出力します。

## コード
```
<?php
$team = ["佐藤","鈴木","田中","岸田","有森"];
foreach ($team as $name) {
    echo $name."さん\n";
}
```

## 出力結果  
```
佐藤さん
鈴木さん
田中さん
岸田さん
有森さん
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | PHP 7.1.15 |
