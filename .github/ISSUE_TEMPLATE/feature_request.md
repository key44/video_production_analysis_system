name: 機能要望 / Feature Request
description: 新しい機能の提案や要望はこちらからお願いします
title: "[Feature]: "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        機能の提案ありがとうございます！現場でより使いやすくするために、ぜひアイデアをお聞かせください。
  - type: textarea
    id: problem
    attributes:
      label: どんな課題を解決したいですか？
      description: 現在のシステムで不便に感じていることや、困っていることを教えてください。
    validations:
      required: true
  - type: textarea
    id: solution
    attributes:
      label: 提案する機能
      description: どのような機能が追加されれば、その課題が解決するか教えてください。
    validations:
      required: true
  - type: textarea
    id: usecase
    attributes:
      label: 現場での活用シーン
      description: その機能が追加された場合、実際の生産改善の現場で「どのように使うか」を具体的に教えてください。
    validations:
      required: true
  - type: textarea
    id: additional_context
    attributes:
      label: その他備考（任意）
      description: その他の要望事項や、参考になる他ツールの例などがあればご記入ください。
    validations:
      required: false
