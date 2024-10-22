# GitHub PR Milestone Check を使ってみよう

リポジトリを新規に作成するとマーケットプレイスのアプリからこのリポジトリに権限を与える選択肢として、 PR Milestone Check が選べるようになりました。

個人または組織単位で有効にでき、2024年10月23日時点では、無料で利用可能になっています。

Organization ではまだ試していないです。所属する Organization の管理者権限が必要かもしれません。

導入したリポジトリで PR を作成して Milestone が未設定だと Status に未設定であることが表示されるようになります。

リポジトリの運用として、 Milestone の設定を必須にしたい場合は、 Rulesets から強制することもできます。

Require status checks to pass から Add checks をクリックして、「mile」で検索すると Milestone Check が選択可能になるので選択します。

正しく設定できると、 Status checks that are required として、 Milestone Check が表示された状態になります。

この状態で PR を確認すると、 Milestone が設定されていないとマージができない状態になります。

Milestone を設定すると、 Status check が動いてマージ可能になります。

Milestone を未設定に戻すと、再び Status check が動いて、マージできない状態になります。
