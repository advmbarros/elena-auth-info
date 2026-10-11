---
title: Política de privacidade — Elena Memórias
---

# Política de privacidade

Última atualização: 11 de outubro de 2026.

## Finalidade e responsável

Elena Memórias é um aplicativo de uso pessoal mantido pelo responsável pela conta GitHub [advmbarros](https://github.com/advmbarros). Sua finalidade é organizar e recuperar informações que o titular escolhe registrar no próprio Google Drive.

## Dados e permissões

O aplicativo solicita autorização OAuth para acessar o Google Drive. A permissão solicitada permite ler e gravar arquivos, e o motor utiliza uma configuração explícita de pastas e IDs para selecionar fontes, entradas e artefatos de memória. O acesso pode incluir conteúdo dos arquivos selecionados, identificadores, tipos, datas, hashes e metadados necessários à validação e recuperação.

Credenciais OAuth permitem executar as rotinas autorizadas sem solicitar login a cada execução. Senhas da conta Google não são coletadas pelo aplicativo. Tokens e segredos não devem ser enviados ao chat nem incluídos em arquivos públicos.

## Armazenamento e processamento

Fontes, entradas e snapshots de memória são armazenados no Google Drive da conta autorizada. O repositório privado GitHub armazena código e configuração; credenciais de execução são armazenadas em GitHub Actions Secrets. O executor GitHub Actions processa temporariamente conteúdos para consolidar e validar a memória. Os comandos são projetados para registrar apenas status e recibos, não conteúdo das memórias.

Quando o titular utiliza uma interface de assistente para registrar ou consultar informações, essa interface também processa o conteúdo solicitado e está sujeita às suas próprias políticas e configurações. Não há promessa de captura integral do histórico de conversas.

## Compartilhamento e uso

O aplicativo não vende dados, não usa memórias para publicidade e não publica conteúdo do Drive nestas páginas. Google, GitHub e a interface de assistente escolhida pelo titular participam do armazenamento ou processamento necessário ao funcionamento.

O uso de informações recebidas das APIs do Google deve respeitar a [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), inclusive os requisitos de Limited Use. O projeto não autoriza utilizar essas informações para treinar modelos de uso geral.

## Retenção e controle

Entradas e gerações são mantidas no Drive para recuperação. Revogar OAuth interrompe o acesso futuro, mas não apaga automaticamente os arquivos já salvos. O titular pode excluir arquivos pelo Drive, remover secrets pelo GitHub e revogar o acesso em [Conexões de terceiros da conta Google](https://myaccount.google.com/connections).

## Segurança e contato

O projeto utiliza validação de conteúdo, hashes e controle de versão para detectar falhas. Esses controles não eliminam todas as falhas de serviços externos. A configuração deve preservar o caráter privado dos dados e limitar o acesso ao titular e às ferramentas autorizadas.

Para contato, utilize o [perfil do responsável no GitHub](https://github.com/advmbarros). Não inclua memórias ou credenciais em mensagens públicas.

Estas páginas não usam formulários, analytics ou cookies próprios. O provedor GitHub Pages pode processar metadados técnicos de acesso conforme sua política.

[Página inicial](index.html) · [Termos de serviço](terms.html)
