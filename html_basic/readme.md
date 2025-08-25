## hot to use
sass/
|-- main.scss
|
|-- foundation/
|   |-- _base.scss       /* HTML要素（body, h1など）の基本スタイル */
|   |-- _reset.scss      /* リセットCSS */
|   |-- _variable.scss   /* 色、フォント、ブレークポイントなどの変数 */
|   `-- _mixin.scss      /* 共通のmixin */
|
|-- layout/
|   |-- _header.scss     /* ヘッダーのレイアウト */
|   |-- _footer.scss     /* フッターのレイアウト */
|   |-- _main.scss       /* メインコンテンツエリアのレイアウト */
|   `-- _sidebar.scss    /* サイドバーのレイアウト */
|
|-- component/
|   |-- _button.scss     /* ボタンのコンポーネント */
|   |-- _card.scss       /* カードのコンポーネント */
|   |-- _form.scss       /* フォームのコンポーネント */
|   `-- _list.scss       /* リストのコンポーネント */
|
|-- project/
|   |-- _project_name.scss  /* 特定のプロジェクトやページのスタイル */
|   `-- _user_profile.scss  /* ユーザープロフィールページ専用のスタイル */
|
|-- utility/
|   |-- _visibility.scss /* 表示・非表示を制御するユーティリティ */
|   `-- _margin.scss     /* 余白を制御するユーティリティ */
|
`-- _import.scss       /* すべてのファイルをインポートする */