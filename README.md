# GREEN X ALLIANCE 公式サイト

一般社団法人グリーンXアライアンスの公式サイト（静的HTML、9ページ）。
デザイン：明るいグリーン #1F8A52 × リーフグリーン #63B44E × 若草がかった白 #F5FAF3（Noto Serif JP + Noto Sans JP、2段ヘッダー、4カラムダークフッター）。DC PLATFORM JAPANと構造は共通、配色で差別化。

## ページ構成
- index.html … トップ（ミッション／ビジョン／役割・組織図／事業領域／研究会／お知らせ）
- about.html … 社団について（法人概要・役割・組織体制）
- business.html … 事業領域（8分野）
- research.html … 研究会（GXA-ABF／GXA-AAF）
- projects.html … プロジェクト
- news.html … お知らせ
- member.html … 会員・参加のご案内
- contact.html … お問い合わせ（Formspree）
- privacy.html … プライバシーポリシー
- style.css / sitemap.xml / robots.txt / CNAME

## 公開手順（GitHub Pages）
1. GitHubで新規リポジトリ作成「GreenXAlliance」（kazumuranaka/GreenXAlliance）
2. 全ファイルをmainブランチにアップロード
3. Settings → Pages → Source: main / (root) で公開
4. Formspreeで新フォームを作成し、contact.html 内の `YOUR_FORM_ID` を差し替え

## ドメイン切替（Wix → GitHub Pages）
1. GitHub Pages の Custom domain に www.greenxalliance.org を設定（CNAMEファイルは同梱済み）
2. ドメイン管理画面（Wixまたはレジストラ）でDNSを変更:
   - www → CNAME: kazumuranaka.github.io
   - @（ルート）→ A: 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
3. 反映後、GitHub Pages で Enforce HTTPS を有効化
4. Google Search Console に sitemap.xml を登録

## 更新方法
各HTMLファイルを直接編集して更新してください（共通部分：ヘッダー・フッターは全ページに同じ記述があります）。
