# Terraformの学習
## 背景
terraformが気になって履いたが、触ったことがなかった。
実務で使う可能性があるので、今のうち学習しておきたい
打ち合わせでインフラ担当と対等に会話できる状態までに持っていくことを目標とする


## 説明
### Terraformとは
- HashiCorp社によってGo言語で作られたツールで、オープンソースとなっている
- infrastructure as codeで、インフラ構成をコードで宣言できます

### infrastructor as codeとは
- インフラのプロビジョニングや更新や削除をコードによって管理できようになります
- 同じコードを使えば、同じ環境をすぐに構築することもできる

### 他のIaCと比べてのメリデメ
- マルチクラウド対応
- ベンダー関係なくこのTerraformのコードが使える
- 各ベンダーの最新サービスへの対応に遅れが出る


### 歴史
- 昔のはサーバーはハード依存であったが、OSの仮想化技術が発展し、仮想サーバーが誕生するようになった
- 2006年にAWSの登場し、簡単に数回クリックするだけで仮想インフラを構築できるようになった
- AWSはコマンドベースでもインフラを簡単に構築・変更できたりします
- そこで2010年、コードを渡すだけで、インフラを構築できるCloud Formationが登場した (infrastructure as code)
- その後にGCPやAzureも登場し、それぞれのクラウド環境も誕生し、それぞれのインフラ構築コードを作るのが大変というのがあった
- そこでTerraformが登場。Terraformの1つのコードを使えば、それぞれのクラウド環境に対応してくれる


## 実務
- infrastructur as codeでインフラを管理する
- ブラウザで操作は使わない




## 参考文献
- [5分で分るTerraform](https://www.lac.co.jp/lacwatch/service/20200903_002270.html)



---

## 学習テンプレート
※ `hoge` を学習するとする

- 背景: `hogeを学習する背景は`
- 説明: `hogeってなに`
    - 一言で
    - hogeまでの技術の歴史
    - 他と比較 (他との違いから説明)
- 学習方法: `hogeの学習マップ`
    - hogeのチュートリアルを実施 (手を動かせるものであれば)
        - + 一言説明できるようにする
    - hogeの商用を意識したものを作る (手を動かせるものであれば)
        - + 商用利用できるイメージをもてるように説明する
- 実務で扱えるようにする: `hogeを商用で利用するとしたら必要な知識 (実務で使うのなら)`
- 参考文献: `学習のメモを残す`