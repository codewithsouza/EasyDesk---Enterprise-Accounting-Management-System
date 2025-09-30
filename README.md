# 🏢 EasyDesk - Sistema de Gestão Contábil

Sistema completo de gestão contábil desenvolvido em Django para controle empresarial, fiscal e de licenciamento.

🔗 *Demo Online:* [https://web-production-52f4.up.railway.app](https://web-production-52f4.up.railway.app)

---

## 📌 Visão Geral

*EasyDesk* é uma plataforma web SaaS para gestão de tarefas contábeis, clientes, conformidade fiscal, licenciamento e auditorias.  
Desenvolvido para escritórios de contabilidade de pequeno a médio porte, centraliza processos operacionais em uma interface limpa e intuitiva.

Suporta múltiplos usuários com acesso baseado em funções, rastreamento de prazos, auditorias internas e integração de dados Excel.

---

## 🚀 Funcionalidades

### 📊 **Gestão de Empresas**
- Cadastro completo com validações de CNPJ e regime tributário
- Gestão de endereços e responsáveis
- Controle de empresas coligadas
- Histórico de alterações e auditoria

### 💼 **Módulo Fiscal**
- Controle de obrigações e integrações fiscais
- Importação/Exportação de dados fiscais
- Apuração por período
- Geração de DARF/GUIAS (quando suportado)
- Indicadores de obrigações em aberto e atrasos

### 📋 **Escrituração Contábil**
- Controle de escrituração por empresa
- Gestão de códigos de escrituração
- Controle de ECD (Escrituração Contábil Digital)
- Acompanhamento de status de escrituração
- Controle de confirmação por responsável
- Gestão de próximas escriturações

### 📚 **Banco de Memórias**
- Base legal contábil organizada por departamento
- Memórias por empresa e assunto
- Categorização por departamento (Comercial, Contábil, Fiscal, Trabalhista)
- Informações resumidas e base legal detalhada
- Controle de assuntos abordados

### 🔔 **Sistema de Notificações**
- Notificações personalizadas por tipo e categoria
- Controle de prioridades (Baixa, Média, Alta, Urgente)
- Agendamento de notificações
- Links de ação direta
- Controle de status (Pendente, Lida, Arquivada)
- Expiração automática de notificações
- Verificação automática de certificados vencidos
- Templates de notificação configuráveis

### 📋 **Licenciamento**
- Controle de licenças e vencimentos
- Gestão de certificados digitais
- Alertas de vencimento automáticos
- Controle de alvarás e licenças

### 👥 **Gestão de Usuários**
- Sistema de autenticação completo
- Controle de permissões por módulo
- Gestão de perfis de usuário
- Auditoria de acessos

### 🔍 **Auditoria**
- Rastreamento completo de alterações
- Log de ações por usuário
- Histórico de modificações
- Controle de integridade dos dados

### 💰 **Módulo Financeiro**
- Gestão financeira integrada
- Controle de receitas e despesas
- Análise de fluxo de caixa
- Relatórios financeiros
- Controle de fornecedores

### 📈 **Dashboard**
- Visão geral do sistema
- Indicadores executivos
- Estatísticas por módulo
- Gráficos e métricas em tempo real

### 📄 **Relatórios**
- Exportação em PDF, Excel e CSV
- Relatórios personalizáveis
- Agendamento de relatórios
- Compartilhamento de relatórios

## 🚀 **Funcionalidades Avançadas**

### 🔄 **Sistema de Notificações Inteligente**
- **Verificação Automática**: Monitora certificados digitais e vencimentos
- **Priorização Inteligente**: Classifica notificações por urgência
- **Agendamento**: Notificações programadas para momentos específicos
- **Templates Configuráveis**: Modelos personalizáveis para diferentes tipos
- **Fila de Processamento**: Sistema robusto para envio em massa
- **Configurações por Usuário**: Preferências individuais de notificação

### 🧠 **Banco de Memórias Contábil**
- **Base Legal Organizada**: Informações fiscais e contábeis por departamento
- **Categorização Inteligente**: Comercial, Contábil, Fiscal e Trabalhista
- **Busca Avançada**: Filtros por empresa, departamento e assunto
- **Histórico Completo**: Rastreamento de consultas e atualizações
- **Relacionamento de Dados**: Conexões entre memórias relacionadas

### 📊 **Dashboard Executivo**
- **Métricas em Tempo Real**: Indicadores atualizados automaticamente
- **Gráficos Interativos**: Visualizações dinâmicas dos dados
- **Filtros Personalizáveis**: Análises por período, empresa ou módulo
- **Exportação de Dados**: Relatórios em múltiplos formatos

### 🔐 **Segurança e Auditoria**
- **Log Completo**: Rastreamento de todas as ações do sistema
- **Controle de Acesso**: Permissões granulares por módulo
- **Integridade de Dados**: Validações e verificações automáticas
- **Backup Automático**: Proteção de dados críticos

---

## 🛠️ Tecnologias

- **Backend:** Django 5.2.4
- **Banco:** MySQL 9.3.0
- **Frontend:** HTML5, CSS3, JavaScript ES6+
- **Deploy:** Railway/Render (configurado)
- **Servidor:** Gunicorn + WhiteNoise

---

## 📁 Estrutura do Projeto

```
easydesk-contabilidade/
├── easydesk/           # Configurações Django
├── empresas/           # Módulo de empresas
├── fiscal/             # Módulo fiscal
├── escrituracao/       # Módulo de escrituração contábil
├── licenciamento/      # Módulo de licenças e certificados
├── dashboard/          # Dashboard e banco de memórias
├── notificacoes/       # Sistema de notificações
├── auditoria/          # Sistema de auditoria
├── financeiro/         # Módulo financeiro
├── usuarios/           # Gestão de usuários
├── accounts/           # Autenticação
├── configuracoes/      # Configurações do sistema
├── core/               # Utilitários centrais
├── utils/              # Funções auxiliares
├── templates/          # Templates HTML
├── static/             # Arquivos estáticos
├── media/              # Uploads e arquivos temporários
├── docs/               # Documentação
├── site/               # Documentação gerada
├── requirements.txt    # Dependências
├── Procfile           # Deploy
└── manage.py          # Django manager
```


---

## 🖼️ Screenshots da Plataforma

### 🔐 Tela de Login
![Login Screen](img/Login.png)

### 📝 Tela de Registro
![Registration Screen](img/register.png)

### 📊 Dashboard Principal
![Main Dashboard](img/Dashboard.png)

### 🧑‍💼 Gestão de Empresas
![Company Management](img/gestão%20de%20empresas%201.png)

### 🧾 Controle Fiscal
![Tax Control](img/Controle%20Fiscal.png)

### 🪪 Licenciamento
![License Management](img/Licenciamento.png)

### 💰 Escrituração Contábil - Parte 1
![Financial Bookkeeping 1](img/Escrituração%201.png)

### 💰 Escrituração Contábil - Parte 2
![Financial Bookkeeping 2](img/Escrituração%202.png)

### 🗄️ Banco de Memórias
![Memory Bank](img/Banco%20de%20memorias.png)

### 🔔 Sistema de Notificações
![Notification System](img/notificacoes.png)

### 📋 Gestão de Tarefas
![Task Management](img/tarefas.png)

---

## 🏃‍♂️ Executar Localmente

### Pré-requisitos
- Python 3.11+
- MySQL 8.0+
- Git

### Instalação

```bash
# 1. Clonar repositório
git clone https://github.com/SEU_USUARIO/easydesk-contabilidade.git
cd easydesk-contabilidade

# 2. Criar ambiente virtual
python -m venv venv
venv\Scripts\activate  # Windows

# 3. Instalar dependências
pip install -r requirements.txt

# 4. Configurar banco MySQL
# Criar banco: CREATE DATABASE easydesk_local;

# 5. Configurar variáveis de ambiente
# Copiar env.example para .env e configurar

# 6. Executar migrações
python manage.py migrate

# 7. Criar superusuário
python manage.py createsuperuser

# 8. Iniciar servidor
python manage.py runserver
```

### Ou usar script automático:
```bash
.\start_easydesk.bat
```

---

## 🌐 Deploy

O sistema está configurado para deploy automático em:

- **Railway** (recomendado) - 500h grátis
- **Render** - Tier gratuito
- **PythonAnywhere** - Python especializado

Consulte `DEPLOY_COMPLETO.md` para instruções detalhadas.

---

## 🎯 Acesso ao Sistema

### 🌐 **URLs Principais**
- **Sistema:** http://localhost:8000
- **Admin:** http://localhost:8000/admin
- **Dashboard:** http://localhost:8000/dashboard/
- **Empresas:** http://localhost:8000/empresas/
- **Fiscal:** http://localhost:8000/fiscal/
- **Escrituração:** http://localhost:8000/escrituracao/
- **Licenciamento:** http://localhost:8000/licenciamento/
- **Notificações:** http://localhost:8000/notificacoes/
- **Banco de Memórias:** http://localhost:8000/banco-memoria/
- **Auditoria:** http://localhost:8000/auditoria/
- **Financeiro:** http://localhost:8000/financeiro/
- **Configurações:** http://localhost:8000/configuracoes/

### 🔧 **APIs Disponíveis**
- **Notificações API:** `/notificacoes/api/`
- **Memórias API:** `/banco-memoria/api/`
- **Tarefas API:** `/tarefas/api/`
- **Dashboard API:** `/dashboard/api/`
- **Health Check:** `/health/`

---

## 🔧 **Monitoramento e Manutenção**

### 📊 **Sistema de Monitoramento**
- **Health Checks**: Verificação de status do sistema
- **Logs Detalhados**: Rastreamento de operações e erros
- **Métricas de Performance**: Monitoramento de recursos
- **Alertas Automáticos**: Notificações de problemas críticos

### 🛠️ **Ferramentas de Manutenção**
- **Migrações Automáticas**: Atualização do banco de dados
- **Backup Automático**: Proteção de dados
- **Limpeza de Cache**: Otimização de performance
- **Verificação de Integridade**: Validação de dados

### 🔄 **Processos Automatizados**
- **Verificação de Certificados**: Monitoramento de vencimentos
- **Geração de Relatórios**: Criação automática de documentos
- **Notificações Programadas**: Alertas em horários específicos
- **Sincronização de Dados**: Atualização entre módulos

---

## 🔧 Desenvolvimento

### Fazer alterações:
```bash
# 1. Editar código
# 2. Testar localmente
python manage.py runserver

# 3. Commit e push
git add .
git commit -m "Descrição da alteração"
git push
```

### Mudanças no banco:
```bash
python manage.py makemigrations
python manage.py migrate
git add .
git commit -m "Nova migração: [descrição]"
git push
```

---

## 📄 Licença

Este projeto é privado e proprietário.

## 👨‍💻 Autor

Desenvolvido para gestão contábil empresarial.

---

**🚀 Sistema pronto para produção!** 

# Deploy test: commit forçado em 2024-08-08 para forçar rebuild Railway