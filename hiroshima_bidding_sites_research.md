# 広島県 公共工事入札データ取得可能サイト 調査結果

調査日: 2026-04-28

---

## 1. 広島県の調達情報ポータル（最重要）

### 1-1. 広島県調達情報サイト（メインポータル）

| 項目 | 内容 |
|------|------|
| URL | https://chotatsu.pref.hiroshima.lg.jp/ |
| 運営 | 広島県土木建築局技術企画課 |
| データ種類 | 入札公告、入札結果、発注見通し、積算関連資料 |
| 無料範囲 | 全て無料・認証不要で閲覧可能 |
| 備考 | 県と市町村の調達情報を集約するポータル |

### 1-2. 広島県電子入札システム

| 項目 | 内容 |
|------|------|
| URL | https://www.e-nyusatsu.dentyo.pref.hiroshima.lg.jp/CALS/Accepter/ |
| データ種類 | 入札公告、入札参加、電子入札の実行 |
| 無料範囲 | 入札情報の閲覧は認証不要で可能 |
| 利用時間 | 9:00〜（時間外はアクセス不可の表示あり） |
| 備考 | 入札参加には電子証明書が必要 |

### 1-3. 広島県電子調達システム（調達情報検索 = PPI）

| 項目 | 内容 |
|------|------|
| URL | https://www.e-chotatsu.dentyo.pref.hiroshima.lg.jp/ppij/PpiJGyomuStart.do?kinouid=GP5000_Top&dantaiCd=34000 |
| データ種類 | 入札公告、入札結果、発注見通し |
| 無料範囲 | 全て無料・認証不要 |
| HTML構造 | フレームベース（iframe）、Java系Webアプリ（.do拡張子 = Struts） |
| スクレイピング | フレーム構造のため難易度高。POSTリクエストの解析が必要。dantaiCdパラメータで自治体切替可能 |
| 備考 | 県と参加市町の入札情報を横断検索可能な最重要システム |

### 1-4. その他の県関連リンク

| ページ | URL |
|--------|-----|
| 電子入札等トップ | https://chotatsu.pref.hiroshima.lg.jp/nyusatsu/index.html |
| 調達情報検索ポータル | https://chotatsu.pref.hiroshima.lg.jp/nyusatsu/ppij/index.html |
| CALS/EC | https://chotatsu.pref.hiroshima.lg.jp/cals/index.html |
| 技術企画課トップ | https://www.pref.hiroshima.lg.jp/soshiki/95/ |

---

## 2. 広島県電子調達システム参加市町村（PPI経由でアクセス可能）

### 電子調達システム（e-chotatsu）参加団体（入札情報を横断検索可能）

| 団体名 | 団体コード | PPI検索URL |
|--------|-----------|------------|
| 広島県 | 34000 | https://www.e-chotatsu.dentyo.pref.hiroshima.lg.jp/ppij/PpiJGyomuStart.do?kinouid=GP5000_Top&dantaiCd=34000 |
| 三原市 | 34204 | ...&dantaiCd=34204 |
| 尾道市 | 34205 | ...&dantaiCd=34205 |
| 三次市 | 34209 | ...&dantaiCd=34209 |
| 廿日市市 | 34213 | ...&dantaiCd=34213 |
| 府中町 | 34302 | ...&dantaiCd=34302 |
| 大崎上島町 | 34431 | ...&dantaiCd=34431 |
| 世羅町 | 34462 | ...&dantaiCd=34462 |
| 神石高原町 | 34545 | ...&dantaiCd=34545 |
| 水道企業団 | 91000 | ...&dantaiCd=91000 |

**ベースURL**: `https://www.e-chotatsu.dentyo.pref.hiroshima.lg.jp/ppij/PpiJGyomuStart.do?kinouid=GP5000_Top&dantaiCd=`

### 独自サイトで入札情報を公開している市町村

| 市町村 | 入札情報URL | データ内容 |
|--------|-----------|-----------|
| 呉市 | https://www.city.kure.lg.jp/~koji/ | 入札公告、入札結果、発注見通し。独自ポータル |
| 竹原市 | https://www.city.takehara.lg.jp/soshikikarasagasu/zaiseika/gyomuannai/3/kensetsukonsaru/1622.html | 建設コンサル入札情報 |
| 福山市 | https://www.city.fukuyama.hiroshima.jp/life/2/17/ | 入札公告、結果、発注見通し、資格者名簿 |
| 府中市 | https://www.city.fuchu.hiroshima.jp/soshiki/kensetubu/kanrika/nyuusatsu/551.html | 入札情報 |
| 庄原市 | https://www.city.shobara.hiroshima.jp/main/government/keiyaku/cat08/ | 契約・入札情報 |
| 大竹市 | http://www.city.otake.hiroshima.jp/jigyosha/1514421466027.html | 入札情報 |
| 東広島市 | https://www.city.higashihiroshima.lg.jp/soshiki/somu/2/index.html | 入札情報（一般競争入札）、資格者名簿 |
| 安芸高田市 | https://www.akitakata.jp/ja/shisei/section/soumu_soumu/nyusatukoukoku/ | 入札公告（建設工事、物品、プロポーザル等） |
| 江田島市 | https://www.city.etajima.hiroshima.jp/cms/categories/show/525 | 入札情報 |
| 海田町 | https://www.town.kaita.lg.jp/life/2/16/101/ | 入札・契約情報 |
| 熊野町 | https://www.town.kumano.hiroshima.jp/www/genre/1437039308948/index.html | 入札情報 |
| 坂町 | https://www.town.saka.lg.jp/category/事業者の方へ/入札・契約/入札・契約-入札・契約/ | 入札・契約情報 |
| 安芸太田町 | https://www.akiota.jp/soshiki/list8-1.html | 入札情報 |
| 北広島町 | https://www.town.kitahiroshima.lg.jp/life/2/13/46/ | 入札情報 |

**注意**: 広島市は独自の電子入札システムを運用（上記ポータルには不参加）

---

## 3. 国の入札情報サービス（PPI / i-PPI）

| 項目 | 内容 |
|------|------|
| URL | https://www.i-ppi.jp/ |
| 運営 | JACIC（一般財団法人 日本建設情報総合センター） |
| データ種類 | 入札公告、入札結果、発注見通し |
| 対象機関 | 国土交通省、農林水産省等の国の機関 + 参加地方公共団体 |
| 無料範囲 | 全て無料・認証不要 |
| HTML構造 | iframe + フレームベース、CSS切替機能あり |
| スクレイピング | フレーム構造のため難易度高。JACIC運営のため利用規約要確認 |
| 広島関連 | 国土交通省中国地方整備局の発注工事が検索可能 |

---

## 4. 民間入札情報サービス

### 4-1. NJSS（入札情報速報サービス）

| 項目 | 内容 |
|------|------|
| URL | https://www2.njss.info/ |
| 運営 | 株式会社うるる |
| データ種類 | 入札公告、落札結果、発注見通し（全国の公共機関） |
| 無料範囲 | 8日間無料トライアル。無料では案件タイトル・機関名のみ閲覧可能。詳細は有料 |
| 有料プラン | 月額制（要問合せ） |
| 特徴 | 業界最大級の案件数・機関数。競合分析機能、類似案件の落札データ分析が可能 |
| スクレイピング | 要ログイン。スクレイピング禁止の可能性高い |

### 4-2. 建設データバンク

| 項目 | 内容 |
|------|------|
| URL | https://www.kensetsu-databank.co.jp/ |
| データ種類 | 建築計画の届出情報（工事看板情報）|
| 無料範囲 | 50,000件以上の建設工事情報が全て無料 |
| 対応地域 | 首都圏中心（東京、神奈川、千葉、埼玉）、中部、関西、北海道、九州 |
| 広島対応 | 限定的（中国地方の対応は不明） |
| 備考 | 入札情報ではなく建築確認申請ベースの情報 |

### 4-3. 建設ネット

| 項目 | 内容 |
|------|------|
| URL | https://www.kensetsu-net.com/ |
| データ種類 | 入札情報検索・閲覧 |
| 広島対応 | 対応あり |
| 無料範囲 | 限定的（要確認） |

---

## 5. 経営事項審査（経審）結果データ

### 5-1. CIIC（建設業情報管理センター）

| 項目 | 内容 |
|------|------|
| URL | https://www.ciic.or.jp/keisin/ |
| 運営 | 一般財団法人 建設業情報管理センター（登録経営状況分析機関 登録番号1） |
| データ種類 | 経営状況分析結果、経審結果の公表 |
| 無料範囲 | 経審結果の公表データは無料閲覧可能 |
| 検索方法 | 都道府県別、業種別で建設業者の経審結果を検索可能 |
| ツール | 「なんでも経審Plus」「CIIC分析パック」等の無料ソフト提供 |
| ISO認証 | ISO 27001取得 |
| 備考 | 広島県の建設業者の総合評定値(P点)を確認可能 |

---

## 6. スクレイピング可能性の総合評価

### 最も取得しやすいサイト（優先順）

| 順位 | サイト | 理由 |
|------|--------|------|
| 1 | 呉市独自ポータル | 静的HTML構造、認証不要、入札結果・発注見通し掲載 |
| 2 | 福山市 | CMSベースだが構造化されたカテゴリページ |
| 3 | 安芸高田市 | シンプルなカテゴリ構造 |
| 4 | 各市町村の独自HP | 静的HTMLが多い |
| 5 | 広島県PPI(e-chotatsu) | フレーム構造+Strutsアプリだが、dantaiCdで自治体切替可能 |
| 6 | 国のPPI(i-ppi.jp) | 同上（フレーム+iframe構造） |

### 技術的ハードル

| サイト | ハードル | 対策 |
|--------|---------|------|
| e-chotatsu系PPI | フレームベース、POSTリクエスト | Seleniumまたはリクエスト解析 |
| i-ppi.jp | 同上 | 同上 |
| NJSS | 要ログイン、スクレイピング禁止 | API利用を交渉 or 手動 |
| 各自治体CMS | CMSごとに構造が異なる | 個別対応 |

---

## 7. データ量の見込み

| ソース | 年間推定件数 |
|--------|------------|
| 広島県（県発注） | 2,000〜3,000件/年 |
| 広島市 | 1,500〜2,500件/年 |
| 福山市 | 500〜1,000件/年 |
| 呉市 | 500〜800件/年 |
| 東広島市 | 300〜500件/年 |
| 廿日市市 | 200〜400件/年 |
| その他市町村（合計） | 1,000〜2,000件/年 |
| 国（中国地方整備局） | 500〜1,000件/年 |
| **合計** | **6,500〜11,200件/年** |

---

## 8. 推奨アプローチ

### Phase 1: 県の電子調達システム（PPI）
- `e-chotatsu.dentyo.pref.hiroshima.lg.jp` のPPIシステムを解析
- dantaiCdパラメータで県+9市町をカバー可能
- Selenium/Playwright でフレーム内のフォーム操作を自動化

### Phase 2: 独自サイトの市町村
- 呉市（~koji/）、福山市、東広島市等の独自サイトを個別スクレイピング
- 比較的シンプルなHTML構造

### Phase 3: 国のPPI
- i-ppi.jp から国土交通省中国地方整備局の発注データを取得

### Phase 4: 経審データ
- CIICの経審結果公表データで建設業者の評点を取得
- 入札結果と組み合わせて分析
