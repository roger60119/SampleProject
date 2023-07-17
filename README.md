# SampleProject

專案主要分成以下三個資料夾，Component、Site、Test

## Component
專案使用到的類別庫，拆分如下
- Core
  - Modules：主要邏輯層
- DataAccess：
  - Caches：快取相關
  - Clients：各種客戶端
  - Entities：類別及實體
  - Interfaces：介面
- DataClass：
  - Attributes：擴充屬性
  - Enumerations：各式列舉
  - Requests：網站請求
  - Responses：網站回應
- Utility：
  - Extensions：擴充方法
  - Helpers：各種小幫手

## Site
網站的主要專案，以 MVC 為例
- SampleProject
  - Controllers：控制器
  - Filters：過濾器
  - Middlewares：中介層
  - Models：模型
  - Views：視覺

## Test
測試專案
- TestProject
  - Client：客戶端測試
  - Core：邏輯層測試
