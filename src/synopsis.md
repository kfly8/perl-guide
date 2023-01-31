# SYNOPSIS

Markdownの表記ルールは、mdBookと基本的に同じです。
異なる点はPerlのコードブロックです。ここではそこを説明します。

このテンプレートを利用すれば、次のようにperlのコードブロックを実行できます。

```perl
print "HELLO WORLD!!"
```


`perl,editable`とコードブロックを書けば、編集可能なコードになります。

```perl,editable
use Test::More;

ok "perl";

done_testing;
```

