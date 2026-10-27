# KO (Hei0MOrld)

自作エフェクター・ベース・電子工作が好きな学生です。自分が困ったことを、小さなWebツールにしています。

## つくったもの

### 部品表(BOM)→ Mouser / DigiKey のカートにするツール
自作の回路の部品表を貼ると、抵抗・コンデンサ・ICなどを値と形状で実在の部品に当てはめて、そのまま注文できるリストにします。実際のMouser・DigiKeyの検索結果をもとに、回帰テストとCIで当てはめの間違いを防いでいます。

| ツール | 対象 | |
|---|---|---|
| [eurorack-bom](https://github.com/Hei0MOrld/eurorack-bom) | Eurorackシンセのモジュール | v1.0 · テスト75件 · 外部のコントリビューターからPR 2件 · [サイト](https://eurorack-bom.vercel.app) |
| [rc2014-bom](https://github.com/Hei0MOrld/rc2014-bom) | RC2014 / Z80の自作コンピューター | v1.0 · テスト34件 · [サイト](https://rc2014-bom.vercel.app) |
| Smart BOM | ギターエフェクター | [サイト](https://smart-bom-eta.vercel.app) |

ModWiggler、diystompboxes.com、RC2014-Z80グループで紹介して、使った人の意見をもとに直しています。

### そのほか
- [company-galaxy](https://github.com/Hei0MOrld/company-galaxy): 約2万4千社の親会社・子会社・株主のつながりを3D/2Dで見られます(Wikidata) · [サイト](https://company-galaxy.vercel.app)
- [kutoten](https://github.com/Hei0MOrld/kutoten): 抜けた句読点を原稿用紙に打ち直す日本語パズル · [サイト](https://kutoten-orpin.vercel.app)

## いま作っているもの
- **ラズパイ5 + Picoのマルチエフェクター**: 回路・配線・ケース・ソフトまで自作しています。ノイズの原因(ブレッドボードのGNDの取り方)を突き止めて、音の部分を基板に組み直すところです。

## 使っているもの
TypeScript · Next.js · Python · Vercel · Supabase · Raspberry Pi · はんだごて

---

**English:** Student maker in Japan. I build small web tools for DIY electronics, mainly BOM-to-Mouser/DigiKey cart tools for [Eurorack](https://github.com/Hei0MOrld/eurorack-bom) and [RC2014](https://github.com/Hei0MOrld/rc2014-bom), each v1.0 with regression tests built from real supplier data. Currently building a Raspberry Pi 5 multi-effects guitar pedal.
