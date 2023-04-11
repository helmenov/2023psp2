# 2023年度　長崎大学　情報データ科学部　2年次　プログラミング演習Ⅱ


## 演習の進め方

[GitHub上の演習ページ][2023psp2@github] にある課題に対して，

- レポート（実行画面のスクリーンショットを含む）
- ソースコードもしくはソースパッケージ

の2点を[LACSの課題ページ][2023psp2@LACS]に提出する．院生TAと薗田が採点し，10点満点未満であれば再提出対象となる．何度でも再提出可能．

- 初めての提出は，課題が提示されてから1週間後の正午までとする．
- この期限を過ぎたあとには，再提出以外は受け付けない．
- この期限までに提出物があった場合，この課題に関わる授業日を「出席」として扱う．逆に何の提出物も無かった場合に「欠席」として扱う．授業日に実際に在席していたかどうかは問わない．

- 最終期限は，課題が提示されてから2週間後の正午までとする．
- この期限を過ぎたあとには，あらゆる提出を受け付けない．

提出は，演習の時間以外でも受け付ける．
### 教室

多目的ホール


### レポートの書き方

```
aa83988848 薗田光太郎

1. 課題
1.1 ......を出力するプログラムを作成せよ．
1.2 ......を出力するプログラムを作成せよ

2. プログラム実行例
(
- 課題小問ごとに，プログラム実行例のスクリーンショット画像を貼る
- どんな入力を行ったのか，を明確に
）
```

### ソースパッケージ

ソースパッケージはフォルダ（例えば`k1`）であり，`k1`という名のフォルダの中に

```
k1
├ k11.py
├ k12.ipynb
├ mymodule
|   ├ module1.py
|   └ module2.py
└ その他実行に必要なリソース（画像やcsvやtxtなどのファイル）
```

のような構造にする．実際にパッケージを提出させる課題を提示する際に指定する．

実行は，

```{.sh}
> python k11.py
```

などで実行して動くものとする．

### Teaching Assistants (TA)

演習当日のプログラミング相談，環境構築のヘルプ，提出物の採点をしてくれるのは，学生ティーチング・アシスタントである．

- 大学院工学研究科情報工学コースの1年生（いわゆる「M1」）を8人

他に，技術職員が参加してくれる．

### プログラミング相談

私のメールアドレスは，

> [kotaro@nagasaki-u.ac.jp](mailto:kotaro@nagasaki-u.ac.jp?subject='プログラミング演習Ⅱ')

です．LACSの「メッセージ（Eメール）」からもメールできます．

メールなどでは伝わりにくい部分もあるので，対面での相談も受け付けます．その場合もあらかじめメールでアポイントをとってください．

## シラバス

[シラバス][2023psp2@NuWEB]

[2023psp2@LACS]:https://lacs.nagasaki-u.ac.jp/webapps/blackboard/content/launchLink.jsp?course_id=_47317_1&toc_id=_966081_1&mode=cpview&mode=reset

[2023psp2@NuWEB]:https://nuweb.nagasaki-u.ac.jp/campusweb/campussquare.do?_flowExecutionKey=_cB119CC41-EC0C-C828-FFA7-77FAD049E721_k7A80501E-B3B6-B9BE-584C-67650BC781F8

[2023psp2@github]:https://github.com/helmenov/2023psp2
