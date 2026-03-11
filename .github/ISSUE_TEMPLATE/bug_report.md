name: バグ報告 / Bug Report
description: バグや不具合の報告はこちらからお願いします
title: "[Bug]: "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        バグ報告ありがとうございます！問題を解決するために、以下の情報をご記入ください。
  - type: input
    id: environment
    attributes:
      label: 環境情報
      description: OS（Windows 11など）やブラウザ（Chrome, Edgeなど）のバージョンをご記入ください。
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: 再現手順
      description: バグを再現するための手順を具体的にご記入ください。
      placeholder: |
        1. 〇〇画面を開く
        2. 〇〇ボタンをクリックする
        3. ...
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: 期待する動作
      description: 本来であればどのように動作するはずだったかをご記入ください。
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: 実際の動作
      description: 実際にはどのような問題が発生したかをご記入ください。
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: スクリーンショット（任意）
      description: 問題の状況がわかるスクリーンショットがあれば添付してください。
    validations:
      required: false
