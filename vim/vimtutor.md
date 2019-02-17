## Vimtutor

### 一括置換
- `#,#s/old/new/g` // #,#は範囲
- `:s/old/new/g` // 全置換
- `:s/old/new/gc` // 確認あり

### 外部コマンド
- `:!<command>`
- `:!ls`
- `:!rm`

### vモーション
visual modeで選択, :w <file>でfileに保存できる (buffer?)

### :r
`:r <file>`でfileの中身を読み込める (read?)

### オープンコマンド
- `o` カーソル下の行を開き挿入モード
- `O` カーソル上の行を開き挿入モード

### 置換(`R`)
---> xxx xxx
---> 123 456
挿入モードとの違いは`既存の文字を削除する`こと

### 検索オプション
- :set ic "Ignore Case
- :set noic
- :set hls "highlight
- :set is "incremental

### 補完
- CTRL-D コマンドの一覧表示
- TAB コマンドの補完
