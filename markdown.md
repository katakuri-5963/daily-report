以下は **README にそのままコピペして使える Markdown 記法一覧**です。

# Markdown 記法一覧（README 用）

よく使う Markdown 記法をまとめています。

---

## 見出し

```md
# 見出し1（h1）

## 見出し2（h2）

### 見出し3（h3）

#### 見出し4（h4）

##### 見出し5（h5）

###### 見出し6（h6）
```

---

## 段落・改行

```md
これは1行目です。

これは空行を挟んだので別の段落になります。

行末にスペースを2つ入れると  
改行できます。
```

---

## 強調

```md
**太字**

_斜体_

**_太字＋斜体_**

~~取り消し線~~
```

表示例：

**太字**  
_斜体_  
**_太字＋斜体_**  
~~取り消し線~~

---

## リスト

### 箇条書き

```md
- 項目1
- 項目2
  - ネスト項目
  - ネスト項目
- 項目3
```

表示例：

- 項目1
- 項目2
  - ネスト項目
  - ネスト項目
- 項目3

---

### 番号付きリスト

```md
1. 項目1
2. 項目2
3. 項目3
```

表示例：

1. 項目1
2. 項目2
3. 項目3

---

## リンク

```md
[Google](https://www.google.com)
```

表示例：

[Google](https://www.google.com)

---

## 画像

```md
![代替テキスト](https://via.placeholder.com/150)
```

---

## コード

### インラインコード

```md
これは `useEffect` の例です
```

表示例：

これは `useEffect` の例です

---

### コードブロック

````md
```js
const message = "Hello";
console.log(message);
```
````

````

表示例：

```js
const message = "Hello";
console.log(message);
````

---

## ファイル名付きコードブロック（推奨）

````md
```jsx
// App.jsx
export default function App() {
  return <h1>Hello</h1>;
}
```
````

````

---

## 引用

```md
> これは引用です
>
> 複数行の引用も可能です
````

表示例：

> これは引用です  
> 複数行の引用も可能です

---

## 区切り線

```md
---
```

表示例：

---

## テーブル

```md
| 名前      | 説明         |
| --------- | ------------ |
| useState  | state を管理 |
| useEffect | 副作用を管理 |
```

表示例：

| 名前      | 説明         |
| --------- | ------------ |
| useState  | state を管理 |
| useEffect | 副作用を管理 |

---

## チェックリスト

```md
- [x] 完了
- [ ] 未完了
```

表示例：

- [x] 完了
- [ ] 未完了

---

## 折りたたみ（GitHub README で便利）

```md
<details>
<summary>クリックして開く</summary>

中身の内容

</details>
```

表示例：

<details>
<summary>クリックして開く</summary>

中身の内容

</details>

---

## バッジ（GitHub README でよく使う）

```md
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
```

---

## コメント（表示されない）

```md
<!-- これは表示されないコメント -->
```

---

## よく使う組み合わせ例（README テンプレ）

````md
# プロジェクト名

説明文

## 技術スタック

- React
- Next.js
- TypeScript

## セットアップ

```bash
npm install
npm run dev
```
````

## ディレクトリ構成

```bash
src/
  components/
  pages/
```

```

---

以上です。
```
