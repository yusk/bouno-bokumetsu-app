# jk

## description

team-appmakerによる煩悩撲滅アプリ

## env

next + redux-thunk + typescript + scss + prettier

## setup
```
cp .env.sample .env
yarn
```

## dev
```
yarn dev
```

## run code formatter
```
yarn lint:fix
```

## deploy
以下動作確認後push
```
yarn set version 4.0.2
sudo rm -rf ./node_modules
yarn
yarn build
```