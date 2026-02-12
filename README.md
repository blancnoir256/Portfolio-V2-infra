# Portfolio-V2-infra
## 目標
作成したサイトをローカルからプッシュするだけで勝手にデプロイされるようにしたい。

## CD
私のポートフォリオサイトの本体であるところの[applicationリポジトリ](https://github.com/blancnoir256/Portfolio-V2-application)と連携しています。

applicationリポジトリの[GithubActions](https://github.com/blancnoir256/Portfolio-V2-application/actions)でapplicationの変更を検知してこちらのリポジトリのmanifest/kustomization.yamlの[tag部分](https://github.com/blancnoir256/Portfolio-V2-infra/blob/main/manifest/kustomization.yaml)を変更することでargoCDによるCDを実現しています。

## 関連
- [bn256.dev](https://bn256.dev)
  - 稀によく止まってます(常に改修工事)
- [Portfolio-V2-application](https://github.com/blancnoir256/Portfolio-V2-application)
