# supportdesk-lab
Laboratório prático de Linux, infraestrutura, Java, SQL, APIs e Spring Boot.

# SupportDesk Lab

Laboratório prático desenvolvido para estudo e aplicação de conhecimentos em **Linux, infraestrutura, redes, APIs REST, SQL e Java**.

O objetivo é transformar o aprendizado teórico em prática, utilizando um ambiente de laboratório, linha de comando, APIs reais e versionamento com Git/GitHub.

---

## 🎯 Objetivo

Construir uma base prática para atuação em áreas de **Suporte Técnico, Infraestrutura, Redes, APIs e QA**, documentando a evolução do aprendizado através de exercícios, experimentos e commits no GitHub.

---

## 🐧 Linux

### Conhecimentos praticados

* Navegação pelo sistema de arquivos
* Criação, cópia, movimentação e exclusão de arquivos e diretórios
* `pwd`
* `ls`
* `cd`
* `mkdir`
* `touch`
* `rm`
* `cp`
* `mv`
* `cat`
* `head`
* `tail`
* `grep`
* `find`
* Processos com `ps`
* Serviços e limitações do ambiente Codespace
* Permissões básicas
* Análise de logs

---

## 🌐 Redes e Infraestrutura

### Conhecimentos praticados

* Endereço IP
* Loopback (`127.0.0.1`)
* TCP
* Portas TCP
* Portas temporárias do cliente
* Portas de serviço
* `ping`
* `ss`
* `nc`
* `getent`
* DNS
* Resolução de nomes
* Tabela de roteamento
* Diagnóstico de conectividade
* Troubleshooting em camadas

### Diagnóstico praticado

```text
DNS
 ↓
IP
 ↓
TCP
 ↓
Porta
 ↓
TLS
 ↓
HTTP/HTTPS
 ↓
API
 ↓
Resposta
```

---

## 🔐 HTTP, HTTPS e TLS

Conhecimentos praticados:

* HTTP
* HTTPS
* Porta 80
* Porta 443
* TLS
* Handshake TLS
* Certificados
* Headers HTTP
* Status HTTP
* Comunicação cliente/servidor

---

## 🔑 SSH

Conhecimentos estudados:

* Porta TCP 22
* Diferença entre serviço SSH e serviço HTTP
* Identificação da porta utilizada por um serviço
* Diagnóstico de conexão TCP

---

## 🚀 API REST

### Métodos praticados

* `GET` — consulta/recuperação de recursos
* `POST` — criação/envio de dados
* `PUT` — atualização completa
* `PATCH` — atualização parcial
* `DELETE` — remoção

### Conceitos praticados

* Endpoint
* Recurso
* Path Parameter
* Query Parameter
* JSON
* Headers
* `Content-Type`
* Status Codes
* HTTP 200
* HTTP 201
* HTTP 404
* HTTP 500
* Requisições com `curl`

### Exemplos praticados

```text
/users/1
/users?id=1
/posts/1
/posts/101
```

---

## 🧪 Troubleshooting de APIs

Foram realizados testes utilizando:

* `curl`
* `ss`
* `nc`
* `getent`
* `ps`
* `tcpdump`

Exemplo de diagnóstico:

```text
DNS → IP → TCP → Porta → TLS → HTTP → API → JSON
```

Também foram analisados casos de:

* conexão recusada;
* porta aberta;
* serviço parado;
* porta incorreta;
* protocolo incorreto;
* erro de requisição;
* erro do servidor;
* resposta HTTP e JSON.

---

## ☕ Java

Java está sendo estudado em paralelo.

Neste laboratório foi criado um servidor HTTP utilizando:

```text
Java
HttpServer
HttpHandler
HttpExchange
```

Endpoint desenvolvido:

```text
GET /api/status
```

Resposta:

```json
{
  "Status": "API funcionando com sucesso!"
}
```

O servidor foi validado utilizando:

```bash
ss -tln
curl
ps
nc
tcpdump
```

---

## 🛠️ Ferramentas

* Linux / Bash
* Git
* GitHub
* GitHub Codespaces
* cURL
* netcat (`nc`)
* `ss`
* `tcpdump`
* `getent`
* Java

---

## 📈 Progresso

### Concluído / praticado

* [x] Linux básico
* [x] Arquivos e diretórios
* [x] Processos
* [x] Logs
* [x] TCP
* [x] Portas
* [x] DNS
* [x] HTTP
* [x] HTTPS
* [x] TLS básico
* [x] SSH básico
* [x] Troubleshooting de conectividade
* [x] API REST — GET
* [x] API REST — POST
* [x] API REST — PUT
* [x] API REST — PATCH
* [x] API REST — DELETE
* [x] Path Parameters
* [x] Query Parameters
* [x] JSON
* [x] Headers básicos
* [x] Status Codes básicos
* [x] Testes de API com cURL
* [x] Servidor HTTP básico em Java

### Próximos estudos

* [ ] Postman
* [ ] Headers em maior profundidade
* [ ] Autenticação de APIs
* [ ] API Key
* [ ] Bearer Token
* [ ] Testes de API no Postman
* [ ] Variáveis no Postman
* [ ] SQL básico
* [ ] SELECT
* [ ] INSERT
* [ ] UPDATE
* [ ] DELETE
* [ ] WHERE
* [ ] ORDER BY
* [ ] LIKE
* [ ] JOIN
* [ ] Integração entre API e banco de dados

---

## 📚 Metodologia

O laboratório prioriza **aprendizado prático**, resolução de problemas e troubleshooting.

Cada etapa é registrada no GitHub para acompanhar a evolução do projeto e manter um histórico das atividades realizadas durante os estudos.
