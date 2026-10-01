# [1.1.0](https://github.com/LaryssaGomes/nestjs-docker-multistage/compare/v1.0.1...v1.1.0) (2026-10-01)


### Features

* add concurrency control for ECS deployments and increase timeout for service stability ([49eec8c](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/49eec8c8cf9a8fc3040859d3932d48d680690268))

## [1.0.1](https://github.com/LaryssaGomes/nestjs-docker-multistage/compare/v1.0.0...v1.0.1) (2026-10-01)


### Bug Fixes

* update GITHUB_TOKEN permissions to allow comments on PRs and issues ([ae4a0e1](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/ae4a0e19f59fc5da6cef64f6af9a5f3c54d8179b))

# 1.0.0 (2026-10-01)


### Bug Fixes

* comment out TypeOrmModule configuration for future use ([19df5fb](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/19df5fb14e8a99813c1d67cca106db6217aa52f3))
* corrigir a ordem das etapas de configuração das credenciais AWS no CI ([d3880a2](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/d3880a273fbf911e4e86d8ec9a7f5d65c9af187b))
* corrigir a referência do sub no papel IAM para incluir o ID do commit ([46b5670](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/46b56708470e58f9d9e034a7cb8bb3a9b593facc))
* corrigir a tag da imagem Docker para usar o formato correto ([44b49e7](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/44b49e73e744bfc17872d4f7577a244996ecb0a9))
* corrigir o caminho do contexto de construção da imagem Docker ([9a0797b](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/9a0797bd422925b39a67453c1098d54d7a9939fc))
* corrigir região da AWS para us-east-1 e remover evento de pull_request ([5b7a2d9](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/5b7a2d9a8e554e01042f95e6591a40aed97c82ec))
* update GITHUB_TOKEN permissions to allow write access for repository checkout ([159c8ed](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/159c8ed27ec54fc29aceb453ab346dbb686008c6))


### Features

* add Docker image tagging and stability wait for ECS deployment ([a5f56b1](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/a5f56b1823eb191b12cf57bc20f2c9f3db441d35))
* add semantic release step to CI workflow ([33e7a7b](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/33e7a7bdaba055fce95e4240ed02d529d83e4f57))
* add working directory configuration for semantic release action ([efe3f55](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/efe3f55be13561c727e5aa41738f4a7e1c36f0c7))
* Adicionar arquivo de configuração CI ([833848a](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/833848a9d824b78ed2b8a54d17a8865d7aa19908))
* Adicionar arquivo package-lock.json ([3d0f36a](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/3d0f36adbaabfc29d755fd42b0b7310932f56693))
* adicionar configuração de ambiente e suporte ao NestJS Config ([47b8fbf](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/47b8fbf4f74059887e0ee0a1f044b3e6e786c1be))
* Adicionar configuração de CI para construção de imagem Docker ([38d681c](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/38d681c3361bf7937df7a67442913226215990e9))
* Adicionar etapa de construção da imagem Docker no CI ([25848e9](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/25848e926f01ef7e52484a2da545db00c1ef7728))
* adicionar etapa para construir e enviar a imagem Docker para o ECR ([19051c9](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/19051c97f00e62304a4a633451cca3c832975c79))
* adicionar etapa para depuração de reivindicações OIDC no CI ([e95de1d](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/e95de1dcefcee259ef85b2ff9009b39df51bf10a))
* Adicionar etapas de geração de tag, login e push da imagem Docker no CI ([6f4b525](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/6f4b5250a952354aa04b46647f0b97ceb46d3162))
* Adicionar etapas de instalação e teste no CI para imagem Docker ([a1d34ef](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/a1d34ef0bc71f6f8ebbd9b292bea5229c496fec5))
* Adicionar multiplos stage ([0d5c738](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/0d5c738e7305829d4a796d1d08197327d90cb1a3))
* Adicionar multiplos stage ([f7fc7b1](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/f7fc7b15c96dd42c151fe5456055194d79bea2ca))
* Adicionar multiplos stage ([23f1376](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/23f1376b8e8b1b08c71654847d58f9d9ba4d99a4))
* adicionar role vinculada ao serviço do ECS para gerenciamento de recursos ([92151d7](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/92151d7676a8a7e56845acad03e8ae47e36ba880))
* atualizar a configuração do Terraform e melhorar o fluxo de CI/CD para o ECR e ECS ([a964070](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/a964070bff82f7471a99bf8d9979f50ff50bbba9))
* Substituir etapas de construção e push da imagem Docker por ação unificada no CI ([b42f6b3](https://github.com/LaryssaGomes/nestjs-docker-multistage/commit/b42f6b3757cdbe6533883d0b4fe46a04f84baf30))
