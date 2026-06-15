# RecToGo プライバシーポリシー・利用規約サイト

RecToGo音声録音アプリの公式プライバシーポリシーと利用規約を提供する多言語対応Webサイトです。

## 🌐 サイトURL

**メインサイト**: https://policy.gorec.moriyatee.com

## 📱 サイト構成

### ホームページ
- **日本語**: [index.html](https://policy.gorec.moriyatee.com/index.html)
- **英語**: [index-en.html](https://policy.gorec.moriyatee.com/index-en.html)

RecToGoアプリの詳細説明、主要機能、料金プラン、対象ユーザー、システム要件を掲載。

### プライバシーポリシー
- **日本語**: [privacy-policy-ja.html](https://policy.gorec.moriyatee.com/privacy-policy-ja.html)
- **英語**: [privacy-policy.html](https://policy.gorec.moriyatee.com/privacy-policy.html)

データ収集、保存方法、セキュリティ、ユーザーの権利について詳細に説明。

### 利用規約
- **日本語**: [terms.html](https://policy.gorec.moriyatee.com/terms.html)
- **英語**: [terms-en.html](https://policy.gorec.moriyatee.com/terms-en.html)

アプリの機能、利用資格、禁止事項、免責事項などの利用条件を記載。

## 🔧 技術仕様

### フレームワーク・技術
- **Jekyll**: 静的サイト生成
- **GitHub Pages**: ホスティング
- **HTML5**: セマンティックマークアップ
- **CSS3**: レスポンシブデザイン
- **JavaScript**: 言語切り替え機能

### 主要機能
- **多言語対応**: 日本語・英語の完全対応
- **言語切り替え**: ページコンテキストを維持した言語切り替え
- **レスポンシブデザイン**: モバイル・デスクトップ対応
- **プロフェッショナルUI**: Google API申請に適したデザイン

## 📁 ファイル構造

```
RecToGo-privacy-policy/
├── index.html                  # 日本語ホームページ
├── index-en.html              # 英語ホームページ
├── privacy-policy-ja.html     # 日本語プライバシーポリシー
├── privacy-policy.html        # 英語プライバシーポリシー
├── terms.html                 # 日本語利用規約
├── terms-en.html             # 英語利用規約
├── assets/
│   ├── css/
│   │   └── style.css         # 統一CSSスタイル
│   └── js/
│       └── language-switch.js # 言語切り替え機能
├── _config.yml               # Jekyll設定
├── CNAME                     # カスタムドメイン設定
└── README.md                 # このファイル
```

## 🎨 デザイン特徴

### カラーパレット
- **プライマリ**: グラデーション（#667eea → #764ba2）
- **セカンダリ**: グレー系（#495057, #6c757d）
- **背景**: ホワイト（#fff）

### レイアウト
- **ヘッダー**: グラデーション背景、言語切り替えボタン
- **ナビゲーション**: 水平メニュー、アクティブ状態表示
- **コンテンツ**: カード形式、グリッドレイアウト
- **フッター**: ダークテーマ、リンク集

### レスポンシブ対応
- **デスクトップ**: 1200px最大幅
- **タブレット**: 768px以下で調整
- **モバイル**: 480px以下で最適化

## 🔄 言語切り替え機能

### 実装方式
JavaScript（`language-switch.js`）による動的ページ遷移

### 対応ページマッピング
```javascript
{
  'index.html': 'index-en.html',
  'terms.html': 'terms-en.html', 
  'privacy-policy-ja.html': 'privacy-policy.html'
}
```

### キーボードショートカット
- **Alt + J**: 日本語に切り替え
- **Alt + E**: 英語に切り替え

## 📝 コンテンツソース

### 利用規約
- **日本語**: `RecToGo/ja.lproj/Localizable.strings`の`terms_content`値
- **英語**: `RecToGo/Resources/terms_en.txt`の全内容

### プライバシーポリシー
- **日本語**: `privacy-policy-ja.md`から変換
- **英語**: `privacy-policy.md`から変換

## 🚀 デプロイメント

### GitHub Pages設定
- **ソース**: mainブランチ
- **カスタムドメイン**: policy.gorec.moriyatee.com
- **HTTPS**: 強制有効

### 自動デプロイ
mainブランチへのプッシュで自動的にサイトが更新されます。

## 🛠️ 開発・メンテナンス

### ローカル開発
```bash
# Jekyll環境セットアップ
bundle install

# ローカルサーバー起動
bundle exec jekyll serve

# ブラウザでアクセス
open http://localhost:4000
```

### ファイル編集時の注意点
1. **利用規約**: RecToGoアプリのソースファイルと完全一致を維持
2. **言語切り替え**: 新ページ追加時は`language-switch.js`を更新
3. **スタイル**: `style.css`で統一されたデザインを維持
4. **Jekyll設定**: 新HTMLページは`_config.yml`に追加

## 📊 SEO・アクセシビリティ

### メタデータ
- **title**: 各ページ固有のタイトル
- **description**: 検索エンジン向け説明文
- **lang属性**: 適切な言語設定

### アクセシビリティ
- **セマンティックHTML**: 適切な見出し構造
- **キーボードナビゲーション**: 全機能にアクセス可能
- **コントラスト**: WCAG準拠の色彩設計

## 📞 サポート・お問い合わせ

技術的な問題やサイトの改善提案は、GitHubのIssuesまたはPull Requestをご利用ください。

---

**開発者**: moriyatee  
**最終更新**: 2025年7月31日  
**ライセンス**: MIT License
