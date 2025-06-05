## チーズを移動する

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/GIjNO1_LHNo?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

チーズ パフを画面上でランダムに動かします。

\--- task ---

**猫**のスプライトを削除します。

\--- /task ---

\--- task ---

新しいスプライトを追加します。 既存のスプライトを選択したり、画像をアップロードしたり、自分のスプライトをペイントしたりすることもできます！ 私たちは **チーズ パフ** スプライトを選択しました。

![「スプライトを選択」オプションが強調表示された「スプライトを選択」メニュー。](images/choose-sprite.png)

\--- /task ---

\--- task ---

スプライトを画面上のランダムな位置に移動させるためのコードを追加します：

```blocks3
when flag clicked
forever
glide (1) secs to (random position v)
```

\--- /task ---

\--- task ---

**テスト:** 緑の旗をクリックして、スプライトが画面上のさまざまな場所にランダムに移動することを確認します。

\--- /task ---

