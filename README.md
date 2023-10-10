<<<<<<< HEAD
## 簡介
此專案為自主練習項目，搭配 .NetCore WebApi 翻新舊有 Asp.Net MVC 圖書管理系統基本功能，WebApi 專案可參考[此處](https://github.com/Shih906/Book-Management-WebApi)
---

## 安裝及啟動
* #### 安裝Node.js npm　:　https://nodejs.org/en/
* #### 安裝 pnpm : npm install pnpm -g
* #### 啟動Server　:　`pnpm dev`

---

## 頁面展示
### 登入與註冊公用元件，含表單驗證

![image](https://github.com/Shih906/Book-Management-FrontEnd-Vue3/assets/88469902/dd100f9c-3d8e-40c1-92f9-dd92810e9fc1)

### 書籍管理分頁搜尋、新增編輯刪除
![image](https://github.com/Shih906/Book-Management-FrontEnd-Vue3/assets/88469902/0b15fb52-85dc-44cc-94c9-4ddd731cbd74)


### 登入人員基本資料設定
![image](https://github.com/Shih906/Book-Management-FrontEnd-Vue3/assets/88469902/41ea7747-6c5e-4295-b720-ae53b7ce7a61)

## 路由配置
| Path | Level | 組件路徑 | 功能 | 
| -------- | -------- | -------- |-------- |
| /login  | 1 | /view/login/LoginPage.vue    |登入、註冊 |
| /  | 1 | /view/layout/LayoutContainer.vue    |Layout樣式 |
| ∣– /books  | 2 | /views/books/BookManage.vue    |書籍管理 |
| ∣– /user/profile  | 2 | /views/user/UserProfile.vue    |基本資料 |

---


## 套件與版本環境
* Vue : 3.3.4
* Vue CLI : 5.0.8
* Vue-router :  4.2.4
* Axios: 1.4.0
* Pinia: 2.1.4
* Element-plus ui : 2.3.9
=======
# BookManageSystem

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
>>>>>>> bff77d4 (Finished BookManage and Profile Page)
