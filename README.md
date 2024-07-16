# lb_trial_z
LastBattalion Trial Patch for X68000Z   by sacokoala

- このパッチは、株式会社スティング 様が公開している「ラストバタリオン　店頭デモ版」を、瑞起 様の［X68000 Z］で動作するように修正するパッチです。

## 修正方法

- 実行には［bup.x］が必要です。
- ラストバタリオンのDiskイメージから、［lb.x］を持ってきます。
- ［lb_z.bfd］を同じ場所に置き、以下のコマンドを実行します。
- > bup lb_z.bfd
- 出来上がったファイル［lb_z.x］を元の名前［lb.x］にリネームして、ラストバタリオンのDiskイメージに書き戻します。
- このDiskイメージを［X68000 Z］でロードすると店頭デモ版が起動します。

## ライセンス

- このパッチ自体は MIT ですが、「ラストバタリオン　店頭デモ版」本体は、株式会社スティング 様の著作物です。取り扱いに注意してください。

- ラストバタリオン（公式HP）
- https://www.sting.co.jp/play/battalion/index.htm

- patch配布場所（sacokoalaのgit）
- https://github.com/sacokoala/lb_trial_z
