#### items.json、useitems.json、ships.jsonとship_affix.jsonについて

KC3改は一部の言語に限って使用できる翻訳がない場合自動的に元の文字列のデータを使う仕様なので、日本語の場合はこのファイルらに`{}`や`[]`だけを入れておけばいい（アイテムと艦娘の名前は元々日本語だから）。
ほかのjsonにおいては使用できる翻訳済みのkeyがない場合、自動的に英語のを使う仕様なので、ご注意を。

#### stype.jsonについて
一部の艦種名は艦これゲームや史実と違うとこがある。二文字に限られて、あくまでも確実に艦種を区別するためのものだから。
それらに疑問を持つならissueを立てて議論をしに来るようお願いします。

#### quotes.jsonについて
一部の修正を除き、主にwikiwiki艦娘ページのセリフをそのままこっちにコピーしたものだから。自分で聞きながら書きたくないなら、あっちの更新を待つしかないね。

wikiwikiからコピーの効率を少し上げるためのTampermonkey User Script: https://gist.github.com/sinsinpub/ed0643b62ef386037de532de4ecd98d3
