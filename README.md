<p align="center">
  <a href="https://www.prefeitura.sp.gov.br/cidade/secretarias/licenciamento/" target="blank">
    <img src="https://www.prefeitura.sp.gov.br/cidade/secretarias/upload/chamadas/URBANISMO_E_LICENCIAMENTO_HORIZONTAL_FUNDO_CLARO_1665756993.png" width="200" alt="SMUL Logo" />
  </a>
</p>

<p align="center">Teste técnico - SMUL/ATIC</p>

## Descrição

Repositório de teste técnico.

Documentação de tecnologia utilizada:

- [NESTJS](https://docs.nestjs.com/)
- [PRISMA](https://www.prisma.io/docs/getting-started)

## Instalação

```bash
npm install
```
## Criando o banco de dados
```bash
npx prisma migrate dev
```
## Rodando o app
```bash
# Modo de monitoramento
npm run dev
```
## Teste Concluido
Foi desenvolvido uma calculadora que executa as 4 operações básicas, com endpoints para realizar as operações e também foi criado endpoints para listagem.

## Endpoints
### Operações Matemáticas
* Adição: POST /operacoes/adicao <br/>
* Subtração: POST /operacoes/subtracao <br/>
* Multiplicação: POST /operacoes/multiplicacao <br/>
* Divisão: POST /operacoes/divisao <br/>

## Consulta de Operações
* Listar Todas as Operações: GET /operacoes/listar <br/>
* Filtrar por Tipo: GET /operacoes/listar?tipo=1 <br/>

## Onde:

* 1 = Adição
* 2 = Subtração
* 3 = Multiplicação
* 4 = Divisão

## Imagens

### Operações:
#### Adição
![adicao](https://github.com/user-attachments/assets/2c2f362e-3000-4a14-895c-dbf7fbaf875d)
#### Subtração
![subtracao](https://github.com/user-attachments/assets/10e07e08-2b0e-41c0-8709-a9dd2ac18164)
#### Multiplicação
![multiplicacao](https://github.com/user-attachments/assets/6cfa85f9-6095-4113-9ce6-734bd44b67f6)
##### Divisão
![divisao](https://github.com/user-attachments/assets/94db8a5f-f726-47f0-92da-fa0efc20af8f)

### Listagem Geral
![listar](https://github.com/user-attachments/assets/51199744-f842-458f-84fe-2b4f047f4072)

### Listagem por tipo:
#### Adição
![ListarPorTipoAdicao](https://github.com/user-attachments/assets/defaeb64-618d-4022-aa1c-fa35aaba26db)
#### Subtração
![ListarPorTipoSubtracao](https://github.com/user-attachments/assets/4baa14f6-7177-4fa8-a807-dbba0937f49e)
#### Multiplicação
![ListarPorTipoMultiplicacao](https://github.com/user-attachments/assets/98cb9d2b-d12f-43b8-b92d-a891725a37c6)
##### Divisão
![ListarPorTipoDivisao](https://github.com/user-attachments/assets/d8dde571-8919-4bcb-9a07-8605e97ae8ec)



