# medical-erp-system
病院経営の「ヒト・モノ・カネ」を最適化する基幹業務エンジン。

## 🏥 システムの役割
- **病院物流管理 (SPD):** 診療材料・医薬品の在庫、発注、消費のリアルタイム管理。
- **資産・メンテナンス管理:** 高額医療機器（MRI/CT等）の法定点検および減価償却の管理。
- **経営ダッシュボード:** 医事会計データと連携した、診療科ごとの収益性およびコストの可視化。

## 🛠 使用フレームワーク・技術
- **Backend:** Java 21 / Spring Boot 3 (堅牢なトランザクション管理)
- **Frontend:** Angular (大規模な業務画面の型安全な制御)
- **Database:** PostgreSQL (データ整合性の確保)
- **Architecture:** Layered Architecture (Domain-Driven Design 志向)
