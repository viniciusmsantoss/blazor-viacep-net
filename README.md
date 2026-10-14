# BlazorViaCep — Consulta de Endereço por CEP (.NET Blazor)

Aplicação Web desenvolvida em **Blazor InteractiveServer** para consulta de endereços em tempo real através do consumo da API pública do **ViaCEP**.

---

## 📌 Informações do Aluno

- **Nome:** Vinícius Miranda
- **RA:** 124114120
- **Curso:** Engenharia de Software (UniBH)
- **Disciplina:** Usabilidade, Desenvolvimento Web, Mobile e Jogos (UDWMJ)
- **Professor:** Daniel Henrique Matos de Paiva

---

## 🚀 Funcionalidades

- Interface reativa com campo para entrada de CEP e validação de formato.
- Consumo assíncrono do endpoint HTTP `GET`: `https://viacep.com.br/ws/{cep}/json/`.
- Mapeamento da resposta JSON para exibição formatada de Logradouro, Bairro, Localidade, UF e CEP.
- Tratamento de exceções e mensagens amigáveis em caso de CEP não encontrado ou inválido.

---

## 🛠️ Tecnologias Utilizadas

- **C# / .NET 10** (ou .NET 8)
- **Blazor InteractiveServer** (`@rendermode InteractiveServer`)
- **HttpClient / System.Net.Http.Json**
- **Bootstrap 5** (estilização e componentes de interface)

---

   ```bash
   git clone [https://github.com/viniciusmsantoss/blazor-viacep-net.git](https://github.com/viniciusmsantoss/blazor-viacep-net.git)
   cd blazor-viacep-net
