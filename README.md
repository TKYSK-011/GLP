# エンジニアの遊び場 - YouTubeチャンネルLP

会社YouTubeチャンネル「エンジニアの遊び場」の公式ランディングページです。IT用語解説ショート動画や社員雑談動画を紹介し、チャンネル登録者数の増加を目指すモバイルファースト設計のWebサイトです。

## 🎯 プロジェクト目的

- **認知拡大**: 自社YouTubeチャンネルの認知度向上
- **登録者増加**: チャンネル登録者数の増加
- **採用促進**: IT業界志望者へのアプローチ
- **ターゲット**: IT業界に興味がある20〜30代、エンジニア志望の求職者

## ✨ 完成機能

### 1. ファーストビュー
- ✅ インパクトのあるキャッチコピー「エンジニアの遊び場」
- ✅ グラデーションテキストエフェクト
- ✅ 最新動画へのCTAボタン
- ✅ チャンネル統計情報の表示（動画数、更新頻度など）
- ✅ スクロールアニメーション

### 2. チャンネル説明（About Us）
- ✅ チャンネルコンセプトの紹介
- ✅ 3つの特徴アイコン（ショート動画、社員雑談、学びと成長）
- ✅ ホバーエフェクト付きカードデザイン

### 3. おすすめ動画ピックアップ
- ✅ IT用語解説ショート動画セクション（縦型レイアウト）
- ✅ 社員雑談動画セクション（横型レイアウト）
- ✅ モバイル最適化グリッド配置（ショート: 2カラム、横長: 1カラム→タブレットで2カラム）
- ✅ 再生ボタンアニメーション
- ✅ 視聴回数・いいね数・投稿日表示
- ✅ すべての動画を見るCTAボタン

### 4. 出演メンバー紹介
- ✅ アバターアイコン（Font Awesome使用）
- ✅ 名前、役職、一言コメント
- ✅ スキルタグ表示
- ✅ ホバーアニメーション

### 5. クロージング・CTA
- ✅ 感謝メッセージ
- ✅ 大きなYouTubeチャンネル登録ボタン（赤色）
- ✅ 会社HP・採用サイトへのリンクボタン
- ✅ SNSフォローリンク（Twitter、Instagram、LinkedIn）

### 6. レスポンシブナビゲーション
- ✅ デスクトップ用横並びナビゲーション
- ✅ モバイル用ハンバーガーメニュー
- ✅ スクロールに応じた背景変化
- ✅ スムーススクロール機能

### 7. インタラクション機能
- ✅ スクロールリビールアニメーション
- ✅ パララックス効果（ヒーローセクション）
- ✅ ホバーエフェクト（カード、ボタン）
- ✅ モバイルメニュートグル
- ✅ アクティブナビゲーションハイライト
- ✅ ページロードフェードイン

## 🎨 デザインテイスト

参考画像のWebサイトデザインを基に以下のテイストで構築：

- **カラースキーム**:
  - プライマリ: ダークブルー（#0a0e1a）
  - アクセント: ブルー（#3b82f6）、パープル（#8b5cf6）
  - テキスト: ホワイト系グラデーション

- **レイアウト**:
  - モバイルファースト設計
  - クリーンでモダンなグリッドレイアウト
  - カードベースのコンテンツ配置

- **タイポグラフィ**:
  - メインフォント: Noto Sans JP（日本語）
  - サブフォント: Roboto（英数字）
  - 階層的なフォントサイズ設定

- **視覚効果**:
  - グラデーション（ブルー→パープル）
  - グローシャドウ
  - ホバーアニメーション
  - スクロールトリガーアニメーション

## 📱 モバイルファースト設計

### YouTubeショート動画の魅力的な表示

- **縦型サムネイル**: アスペクト比 9:16 でスマホに最適化
- **2カラムグリッド**: モバイルで見やすい配置
- **大きな再生ボタン**: タップしやすいサイズ
- **SHORTSバッジ**: 視覚的な識別

### レスポンシブブレイクポイント

1. **モバイル（〜767px）**: 
   - シングルカラム基本
   - ショート動画は2カラム
   - ハンバーガーメニュー

2. **タブレット（768px〜1023px）**:
   - 2〜3カラムグリッド
   - ショート動画は4カラム
   - デスクトップナビゲーション

3. **デスクトップ（1024px〜）**:
   - 最大4カラムグリッド
   - フルワイドレイアウト
   - 拡張されたスペーシング

## 🚀 技術スタック

- **HTML5**: セマンティックマークアップ
- **CSS3**: 
  - CSS Variables（カスタムプロパティ）
  - Flexbox & Grid Layout
  - カスタムアニメーション
  - メディアクエリ
- **JavaScript (Vanilla)**:
  - Intersection Observer API（スクロールアニメーション）
  - イベントリスナー（メニュー、スクロール）
  - DOM操作
- **外部ライブラリ**:
  - Google Fonts（Noto Sans JP, Roboto）
  - Font Awesome 6.4.0（アイコン）

## 📁 ファイル構造

```
/
├── index.html          # メインHTMLファイル
├── css/
│   └── style.css       # メインスタイルシート
├── js/
│   └── script.js       # JavaScriptインタラクション
└── README.md           # プロジェクトドキュメント
```

## 🎬 主要セクション

1. **Hero Section** (`/`): 
   - キャッチコピー
   - 統計情報
   - メインCTA

2. **About Section** (`/#about`):
   - チャンネル紹介
   - 3つの特徴

3. **Videos Section** (`/#videos`):
   - IT用語解説ショート（4動画）
   - 社員雑談動画（2動画）
   - YouTube遷移CTA

4. **Members Section** (`/#members`):
   - 出演メンバー（4名）
   - 役職・コメント・スキルタグ

5. **CTA Section**:
   - 感謝メッセージ
   - チャンネル登録CTA
   - 会社HP・採用サイトリンク
   - SNSフォロー

6. **Footer**:
   - ロゴ
   - リンク集
   - コピーライト

## 🔧 カスタマイズ方法

### 1. 動画情報の更新

`index.html` の該当セクションを編集：

```html
<!-- ショート動画例 -->
<div class="short-card">
    <div class="short-thumbnail">
        <!-- 背景画像を追加する場合: style="background-image: url('画像URL')" -->
    </div>
    <div class="short-info">
        <h4>動画タイトル</h4>
        <p>説明文</p>
        <div class="short-stats">
            <span><i class="fas fa-eye"></i> 10K</span>
            <span><i class="fas fa-thumbs-up"></i> 520</span>
        </div>
    </div>
</div>
```

### 2. メンバー情報の変更

```html
<div class="member-card">
    <div class="member-avatar">
        <i class="fas fa-user-tie"></i> <!-- アイコン変更可能 -->
    </div>
    <h3 class="member-name">名前</h3>
    <p class="member-role">役職</p>
    <p class="member-comment">「コメント」</p>
    <div class="member-tags">
        <span class="tag">スキル1</span>
        <span class="tag">スキル2</span>
    </div>
</div>
```

### 3. カラーテーマの変更

`css/style.css` の CSS Variables を編集：

```css
:root {
    --color-accent-blue: #3b82f6;    /* メインアクセントカラー */
    --color-accent-purple: #8b5cf6;  /* セカンダリカラー */
    /* その他のカラー変更 */
}
```

### 4. YouTube動画へのリンク設定

`js/script.js` の動画カードクリックハンドラーを編集：

```javascript
document.querySelectorAll('.short-card, .long-card').forEach(card => {
    card.addEventListener('click', () => {
        window.open('実際のYouTube動画URL', '_blank');
    });
});
```

または、各カードに直接リンクを追加：

```html
<a href="https://youtube.com/watch?v=VIDEO_ID" target="_blank" class="short-card">
    <!-- カード内容 -->
</a>
```

### 5. 会社HP・採用サイトのリンク設定

`index.html` のCTAセクション内のボタンURLを更新：

```html
<a href="https://your-company-website.com" class="btn btn-outline">
    <i class="fas fa-building"></i>
    会社HPを見る
</a>
<a href="https://your-recruitment-site.com" class="btn btn-outline">
    <i class="fas fa-briefcase"></i>
    採用情報を見る
</a>
```

## 📊 パフォーマンス最適化

- ✅ CSS Variables使用による効率的なスタイル管理
- ✅ Intersection Observer APIによる効率的なアニメーション
- ✅ モバイルファースト設計によるパフォーマンス向上
- ✅ CDN経由のフォント・アイコン読み込み
- ✅ 最小限のJavaScript依存

## 🔄 今後の実装予定機能

### 優先度: 高
- [ ] 実際のYouTube動画埋め込み（iframe）
- [ ] YouTube Data APIとの連携（自動的に最新動画を取得）
- [ ] 動画モーダルウィンドウ機能
- [ ] お問い合わせフォーム

### 優先度: 中
- [ ] 動画検索・フィルター機能
- [ ] ダークモード/ライトモード切り替え
- [ ] チャンネル登録者数のリアルタイム表示
- [ ] ブログ/記事セクション

### 優先度: 低
- [ ] 多言語対応（英語版）
- [ ] アクセス解析（Google Analytics）統合
- [ ] A/Bテスト機能
- [ ] コメント機能

## 🎯 推奨される次のステップ

1. **実際のYouTube動画URLを各カードに設定**
   - ショート動画4本のURL
   - 雑談動画2本のURL

2. **会社情報の更新**
   - 会社HPのURL設定
   - 採用サイトのURL設定
   - 実際のSNSアカウントへのリンク

3. **メンバー情報の実名・実データへの更新**
   - 実際の出演メンバー情報
   - プロフィール写真の追加（推奨）

4. **YouTube Data APIの統合**
   - 自動的に最新動画を表示
   - 視聴回数・いいね数のリアルタイム取得

5. **SEO対策**
   - meta description最適化
   - OGP（Open Graph Protocol）タグ追加
   - 構造化データ（JSON-LD）追加

6. **アクセス解析の設定**
   - Google Analytics導入
   - コンバージョントラッキング設定

## 📝 使用上の注意

- **YouTubeリンク**: 現在はプレースホルダーです。実際の動画URLに置き換えてください。
- **画像**: サムネイル画像は背景グラデーションで代用しています。実際の動画サムネイル画像の追加を推奨します。
- **外部リンク**: 会社HP・採用サイトのリンクは "#" になっています。実URLに更新してください。
- **SNSリンク**: フッターのSNSリンクも実際のアカウントURLに更新が必要です。

## 🌐 ブラウザ対応

- ✅ Chrome（最新版）
- ✅ Firefox（最新版）
- ✅ Safari（最新版）
- ✅ Edge（最新版）
- ✅ モバイルブラウザ（iOS Safari、Chrome Mobile）

## 📄 ライセンス

© 2026 Engineer's Playground. All rights reserved.

---

## 🎉 デプロイ方法

**Publishタブで簡単デプロイ！**

このプロジェクトをオンラインで公開するには：

1. **Publishタブ**に移動
2. **公開ボタン**をクリック
3. 自動的にWebサイトがデプロイされます
4. 公開URLが発行されます

デプロイ後、YouTube、SNS、採用サイトなどでLPのURLを共有してチャンネル登録を促進しましょう！

---

**開発者**: Static Website Builder
**最終更新**: 2026-01-27