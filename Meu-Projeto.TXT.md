# 📚 Tutorial: Criação de Repositório no GitHub com GitHub Desktop




> **Curso:** Sistemas para Internet – IFMT Campus Cuiabá Cel. Octayde Jorge da Silva

---

## 👥 Integrantes do Projeto

| Nome | Papel |
|------|-------|
| Igor | Desenvolvedor |
| Aline | Desenvolvedora |
| Emerson | Desenvolvedor |
| Thiago | Desenvolvedor |

---

## 🎯 Introdução

O **controle de versões** é uma prática essencial no desenvolvimento de software, pois permite:

✅ Registrar alterações realizadas em arquivos  
✅ Manter histórico de modificações  
✅ Facilitar trabalho colaborativo entre desenvolvedores  

O **GitHub** é a plataforma mais utilizada para hospedagem e gerenciamento de projetos. Este tutorial apresenta, de forma clara e acessível, como criar um repositório e fazer o primeiro commit usando **GitHub Desktop**.

---

## 📋 Requisitos e Materiais Necessários

Antes de iniciar, verifique se os seguintes requisitos foram atendidos:

| Requisito | Status |
|-----------|--------|
| 💻 Windows 10 ou superior | ✓ |
| 🌐 Conexão ativa com internet | ✓ |
| 🔐 Conta cadastrada no GitHub | ✓ |
| 🌍 Navegador web instalado | ✓ |
| 🖥️ GitHub Desktop instalado | ✓ |
| 📖 Conhecimento básico de computadores | ✓ |

> ⚠️ **Nota:** Caso ainda não possua conta no GitHub, realize previamente o cadastro na [plataforma oficial](https://github.com/signup).

---

## 🚀 Procedimento Técnico (Passo a Passo)

### 📌 Passo 1: Acesse o Site Oficial do GitHub

```
1. Abra o navegador de internet
2. Digite: https://github.com
3. Pressione Enter
```

**✅ Resultado Esperado:**
- A página inicial do GitHub será exibida

![GitHub Homepage](https://github.com/images/modules/logos_page/GitHub-Mark.png)

---

### 📌 Passo 2: Realize o Login na Plataforma

```
1. Clique na opção "Sign in" (Entrar)
2. Digite o endereço de e-mail cadastrado
3. Digite a senha
4. Clique em "Sign in" (Entrar)
```

**✅ Resultado Esperado:**
- O sistema direciona o usuário para a página principal da conta

---

### 📌 Passo 3: Crie um Novo Repositório

#### 3.1 - Inicie a Criação

```
1. Clique no símbolo "+" localizado na parte superior direita
2. Selecione "New Repository" (Novo Repositório)
```

#### 3.2 - Preencha os Campos

| Campo | Descrição | Obrigatório |
|-------|-----------|------------|
| **Repository name** | Nome do repositório | ✅ Sim |
| **Description** | Descrição do projeto | ❌ Opcional |
| **Public / Private** | Visibilidade do repositório | ✅ Sim |

#### 3.3 - Marque a Opção

```
☑ Add a README file (Adicionar um arquivo README)
```

#### 3.4 - Finalize

```
Clique em "Create repository" (Criar Repositório)
```

**✅ Resultado Esperado:**
- Novo repositório criado com sucesso

---

### 📌 Passo 4: Abra o GitHub Desktop

```
1. Localize o GitHub Desktop no computador
2. Execute o programa
3. Realize login com a mesma conta cadastrada
```

**✅ Resultado Esperado:**
- Tela principal do GitHub Desktop será exibida

---

### 📌 Passo 5: Clone o Repositório Criado

#### 5.1 - Inicie a Clonagem

```
1. Clique em: File → Clone Repository (Clonar Repositório)
```

#### 5.2 - Selecione e Configure

```
1. Selecione o repositório criado anteriormente
2. Escolha a pasta onde os arquivos serão armazenados
3. Clique em "Clone" (Clonar)
```

**✅ Resultado Esperado:**
- Repositório copiado para o computador local

---

### 📌 Passo 6: Realize o Primeiro Commit

#### 6.1 - Crie um Arquivo

```
1. Crie um arquivo chamado: meu-projeto.txt
```

#### 6.2 - Adicione Conteúdo

```
Digite a seguinte mensagem:
"Primeiro teste de repositório GitHub"
```

#### 6.3 - Salve o Arquivo

```
Salve o arquivo na pasta clonada do repositório
```

#### 6.4 - Retorne ao GitHub Desktop

```
1. Abra GitHub Desktop
2. Você verá o arquivo criado na aba "Changes"
```

#### 6.5 - Realize o Commit

```
1. No campo "Summary" (Resumo), digite:
   "Primeiro commit"
   
2. No campo "Description" (Descrição), tipo (opcional):
   "Salvando alterações na ramificação principal"
   
3. Clique em "Commit to main" (Commit na ramificação principal)
```

#### 6.6 - Envie para o Repositório Online

```
1. Clique em "Push origin" (Enviar alterações)
```

**✅ Resultado Esperado:**
- Alterações enviadas ao repositório online com sucesso

---

## ⚠️ Alertas e Boas Práticas

### 🚫 Atenção - Pontos Críticos

| ⚠️ Alerta | Descrição |
|----------|-----------|
| **Atenção 1** | Nunca compartilhe senhas ou credenciais de acesso |
| **Atenção 2** | Revise cuidadosamente arquivos antes de fazer o envio |
| **Atenção 3** | Evite publicar informações pessoais em projetos públicos |
| **Atenção 4** | Não compartilhe dados sensíveis em repositórios abertos |

### ✅ Boas Práticas Recomendadas

```
✓ Utilize mensagens descritivas em commits
✓ Faça commits frequentes e pequenos
✓ Sincronize com a equipe regularmente
✓ Revise o código antes de enviar
✓ Mantenha a organização das pastas
✓ Use branches para features novas
✓ Documente alterações importantes
```

---

## 🎯 Resultado Esperado

Ao concluir todas as etapas descritas neste tutorial, você deverá possuir:

- ✅ Conta autenticada no GitHub
- ✅ Repositório criado com sucesso
- ✅ Repositório clonado localmente
- ✅ Primeiro commit realizado
- ✅ Sincronização entre computador e plataforma online

### 🔍 Verificação

Para confirmar que tudo funcionou corretamente:

```
1. Acesse seu repositório no GitHub
2. Verifique a presença do arquivo enviado
3. Confirme o histórico de commits
4. Valide a data e hora do push
```

---

## 📚 Estrutura de Pastas Recomendada

```
seu-repositorio/
├── README.md                    # Documentação principal
├── TUTORIAL_GITHUB_DESKTOP.md   # Este arquivo
├── src/                         # Código-fonte
│   ├── index.js
│   ├── components/
│   └── utils/
├── docs/                        # Documentação adicional
├── tests/                       # Testes
├── .gitignore                   # Arquivos ignorados
├── LICENSE                      # Licença do projeto
└── package.json                 # Dependências (se aplicável)
```

---

## 🔗 Referências e Recursos

| Recurso | Link |
|---------|------|
| 📖 GitHub Documentation | [docs.github.com](https://docs.github.com) |
| 🖥️ GitHub Desktop Docs | [desktop.github.com](https://desktop.github.com) |
| 📚 GitHub Guides | [guides.github.com](https://guides.github.com) |
| 🎓 GitHub Learning Lab | [lab.github.com](https://lab.github.com) |

### Normas Técnicas Utilizadas

- **ABNT NBR 6023** – Informação e documentação — Referências
- **ABNT NBR 14724** – Informação e documentação — Trabalhos acadêmicos

---

## 📞 Suporte e Dúvidas

Se encontrar problemas durante o processo:

```
1. Verifique a conexão com internet
2. Confirme se o GitHub Desktop está atualizado
3. Valide suas credenciais de acesso
4. Consulte a documentação oficial do GitHub
5. Entre em contato com o suporte técnico
```

---

## 📝 Changelog

| Data | Versão | Alterações |
|------|--------|-----------|
| 20/05/2026 | 1.0 | Criação do tutorial inicial |

---

## 👨‍💼 Informações do Projeto

- **Instituição:** IFMT Campus Cuiabá Cel. Octayde Jorge da Silva
- **Curso:** Sistemas para Internet
- **Tipo:** Tutorial Técnico
- **Público-Alvo:** Iniciantes em Git/GitHub
- **Nível:** Básico

---

## 📄 Licença

Este tutorial é fornecido como material educacional para fins de aprendizagem.

---

<div align="center">

**Feito com ❤️ para a comunidade de desenvolvimento**

*Última atualização: 20 de maio de 2026*

</div>
