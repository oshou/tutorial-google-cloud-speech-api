## 本レポジトリについて
音声ファイルを渡すと内容をテキスト化するスクリプト
Google Cloud Speech API使用。

## 参照元
REST API 音声認識チュートリアル
- https://cloud.google.com/speech/docs/rest-tutorial

## 事前準備
事前に以下URLよりGoogleAPIキーの作成を行う。
- https://codelabs.developers.google.com/codelabs/cloud-speech-intro-ja/index.html

## 実行手順
1. $ export GOOGLE_APPLICATION_CREDENTIALS = /path/to/service_account_file.json
2. $ export GCLOUD_PROJECT = your-project-id
3. $ python tutorial.py audio.raw
