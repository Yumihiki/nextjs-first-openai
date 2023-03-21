## このアプリについて

Next.jsとOpenAPIを利用したアプリケーションです。

## 作成方法

環境の作成は以下の手順で行ってください。

```zsh
mkdir nextjs-first-openai
cd nextjs-first-openai
npx create-next-app

cd nextjs-first-openai 
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
touch .env.local 
```

.env.local では以下のようにAPIキーを入力してください。
```.env.local
NEXT_PUBLIC_API_KEY=APIキーを入力
```

動かしたい場合
```zsh
npm run dev
```

## 参考記事

https://dev.classmethod.jp/articles/first-openai-app-in-nextjs-with-tailwindcss/