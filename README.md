# Mavenの利用法 [ for macOS ]

## 利用環境
1. OS : macOS 10.12.3
2. Javac : 1.8.0_112
3. Java : 1.8.0_112
4. Maven : 3.3.9

## インストール
```
$ brew install maven
```

## プロジェクトテンプレートの生成
```
$ mvn archetype:generate -DgroupId=com.example.app -DartifactId=sample -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

## プロジェクトのチェック
```
$ mvn validate
```

## コンパイル
```
$ mvn compile
```

## テスト
```
$ mvn test
```

## ドキュメントの生成
```
$ mvn site
```

## ビルド結果の削除
```
$ mvn clean
```
