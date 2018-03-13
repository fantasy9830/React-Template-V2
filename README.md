React後臺管理系統

## 注意事項

* `/src/stores.js` 和 `/src/components/Auth/action.js` 已註解掉登入相關程式，改用假資料登入，故帳號密碼可隨意輸入。

* `/src/components/Layout/Notice/socketio.js` 已註解掉WebSocket相關程式。

* 權限相關程式
  * 路由權限：`/src/utils/renderAuthRoutes.js`
  * SiderBar Menu權限(HOC)：`/src/components/Auth/check.js`

* 路由參數(`/src/routes.js`)
  * auth: 是否要登入後才能顯示。
  * menu: 權限代碼，相關權限由此定義。
