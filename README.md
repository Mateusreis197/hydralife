# HydraLife - Controle de Hidratação

## Descrição do Projeto
O HydraLife é uma aplicação simples em linha de comando (CLI) desenvolvida para auxiliar usuários no monitoramento da ingestão diária de água.

A aplicação permite registrar o consumo de água ao longo do dia e acompanhar o progresso em relação a uma meta diária recomendada, contribuindo para a promoção de hábitos saudáveis.

## Problema Real
Muitas pessoas não ingerem a quantidade ideal de água diariamente, seja por esquecimento ou falta de controle. Isso pode resultar em desidratação, fadiga e outros impactos negativos na saúde.

## Proposta de Solução
O HydraLife oferece um mecanismo simples e acessível para controle de hidratação, permitindo que o usuário:
- registre a quantidade de água consumida;
- acompanhe o progresso diário;
- verifique quanto falta para atingir a meta recomendada.

## Público-Alvo
- Estudantes
- Trabalhadores com rotina intensa
- Pessoas interessadas em melhorar hábitos de saúde
- Público em geral

## Funcionalidades
- Registro de consumo de água (em mililitros)
- Visualização do progresso diário
- Verificação do status da meta de hidratação
- Validação de entradas inválidas

## Tecnologias Utilizadas
- Python 3
- JSON para armazenamento de dados
- Pytest para testes automatizados
- Ruff para análise estática de código
- GitHub Actions para integração contínua

## Instalação

1. Clonar o repositório:
git clone https://github.com/seuusuario/hydralife.git

2. Acessar a pasta:
cd hydralife

3. Instalar dependências:
pip install -r requirements.txt

## Execução da Aplicação
python src/app.py

## Execução dos Testes
pytest

## Análise Estática (Lint)
ruff check .

## Integração Contínua
O projeto utiliza GitHub Actions para executar automaticamente:
- instalação das dependências
- verificação de código (lint)
- execução dos testes

## Estrutura do Projeto
hydralife/
├── src/
│   └── app.py
├── tests/
│   └── test_app.py
├── data.json
├── requirements.txt
├── README.md
├── VERSION
├── .github/workflows/ci.yml

## Versionamento
Versão atual: 1.0.0

## Exemplo de Uso
1 - Adicionar água
2 - Ver progresso
3 - Sair

Exemplo:
Usuário adiciona 500 ml
Sistema mostra progresso total e quanto falta para meta

## Autor
Mateus Andrade

## Repositório
https://github.com/seuusuario/hydralife

## Licença
MIT
