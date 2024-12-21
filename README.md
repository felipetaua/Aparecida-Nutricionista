# Aparecida Nutrição

Este é um projeto para gerenciar informações de pacientes, incluindo cálculo de IMC (Índice de Massa Corporal), filtros dinâmicos e adição de novos pacientes. O objetivo é fornecer uma interface amigável para nutricionistas organizarem dados e acompanharem os resultados de seus pacientes.

[![Live Server](https://img.shields.io/badge/Live_Server-Click_Here-brightgreen?style=for-the-badge)](https://felipetaua.github.io/Aparecida-Nutricionista/)
---

## 📋 **Descrição do Projeto**

### Funcionalidades Principais:
1. **Listagem de Pacientes**:
   - Exibe informações como nome, peso, altura, porcentagem de gordura e IMC.
   - IMC calculado automaticamente com base nos dados informados.

2. **Adicionar Novo Paciente**:
   - Formulário para incluir dados de novos pacientes.
   - Validação de campos para garantir dados consistentes.

3. **Filtrar Pacientes**:
   - Campo de busca para filtrar pacientes por nome.

4. **Remoção de Pacientes**:
   - Clique em um paciente para removê-lo da tabela.

5. **Busca de Pacientes via API**:
   - Botão para carregar uma lista de pacientes de uma API externa (mocked).

6. **Exibição de Mensagens de Erro**:
   - Mensagens de validação e erros exibidas dinamicamente.

---

## 🛠 **Tecnologias Utilizadas**
- **HTML5**: Estrutura da página.
- **CSS3**: Estilização para uma interface moderna.
- **JavaScript**: Manipulação da DOM e lógica de validação/calculadora de IMC.

---

## 🚀 **Como Executar o Projeto**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/aparecida-nutricao.git
   ```
2. Abra o arquivo `index.html` em seu navegador.
3. Utilize as funcionalidades de listagem, cálculo de IMC, adição de pacientes e filtros.

---

## 📚 **Estrutura de Arquivos**

```
/aparecida-nutricao
│
├── css/
│   ├── reset.css       # Reset de estilos para uniformizar o layout
│   ├── index.css       # Estilização do projeto
│
├── js/
│   ├── calcula-imc.js         # Cálculo automático de IMC
│   ├── form.js                # Validação e adição de pacientes
│   ├── remover-paciente.js    # Remoção dinâmica de pacientes
│   ├── filtra.js              # Filtro de pacientes por nome
│   ├── buscar-pacientes.js    # Integração com API simulada
│
├── index.html        # Estrutura principal da página
└── favicon.ico       # Ícone do site
```

---

## 🌟 **Funcionalidades Futuras**
- Adicionar gráficos para monitorar a evolução dos pacientes.
- Exportar dados para formatos como CSV ou PDF.
- Melhorar a interação com APIs externas para carregamento de dados.

---

## 🖋 **Créditos**
Criado por: **Tauã Felipe Rocha Amaro**  
Curso: **Técnico em Desenvolvimento de Sistemas (TDS) - 2024**

--- 

Divirta-se utilizando o **Aparecida Nutrição**!
