# Sidebar-UI
Minecraft Bedrock Edition の JSON UI を使った カスタムSidebar です

> ちなみに動作確認はしっかりしてません。

#使い方
1. アドオンをダウンロード
2. 自分のわーるどに適応
3. 以下の方法（ScriptAPIを使用した方法でも可能)でアクションバーを表示
```cmd
/title @a actionbar "アクションバーのテキスト:/:サイドバーのテキスト" //:/:で区切る
```

## +α タイトルを変えたい場合
1. ui/hud_screen.json を開く
2. 45行目（actionbar_sidebar > main > title) 内の text の先を変更する
