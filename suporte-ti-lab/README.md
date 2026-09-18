# Suporte TI Lab

Projeto autoral de laboratório para praticar rotinas de **Suporte de TI**, reunindo cenários de atendimento, diagnóstico e documentação técnica.

> Este projeto é independente e não possui vínculo oficial com nenhuma empresa.

## Objetivo

Simular o trabalho de um analista de suporte N1/N2 em uma empresa, praticando:

- Instalação, configuração e troubleshooting de sistemas operacionais;
- Diagnóstico de hardware e periféricos;
- Fundamentos de redes TCP/IP, IP, DNS e Wi-Fi;
- Administração básica de Microsoft 365 e Active Directory;
- Uso de ferramentas de acesso remoto;
- Atendimento ao usuário e comunicação técnica;
- Registro, priorização e encerramento de chamados.

## Cenários simulados

1. Computador com lentidão no Windows;
2. Impressora sem comunicação com a estação;
3. Usuário sem acesso à rede Wi-Fi;
4. Falha de resolução de nomes via DNS;
5. Solicitação de criação ou desbloqueio de usuário;
6. Problema de acesso ao Microsoft 365;
7. Atendimento remoto com validação de identidade;
8. Equipamento que não liga;
9. Usuário com dificuldade para utilizar uma aplicação corporativa;
10. Incidente que precisa ser escalonado para o suporte N2.

## Estrutura do projeto

```text
suporte-ti-lab/
├── README.md
├── checklists.md
├── procedimentos/
│   ├── windows.md
│   ├── hardware.md
│   ├── redes.md
│   ├── microsoft-365-ad.md
│   └── acesso-remoto.md
└── chamados/
    └── modelo-chamado.md
```

## Fluxo de atendimento

```text
Receber chamado
      ↓
Validar usuário e impacto
      ↓
Coletar evidências
      ↓
Executar diagnóstico
      ↓
Aplicar solução segura
      ↓
Validar com o usuário
      ↓
Documentar e encerrar
```

## Tecnologias e ferramentas estudadas

- Windows;
- Fundamentos de Linux e macOS;
- TCP/IP, DNS, DHCP e Wi-Fi;
- Microsoft 365;
- Active Directory;
- Ferramentas de acesso remoto;
- PowerShell básico;
- Documentação em Markdown;
- Git e GitHub.

## Competências demonstradas

- Troubleshooting;
- Raciocínio lógico;
- Comunicação com usuários;
- Organização de chamados;
- Análise de causa provável;
- Documentação técnica;
- Priorização por impacto e urgência.

## Próximas evoluções

- Criar uma aplicação web para registrar chamados;
- Adicionar banco de dados PostgreSQL;
- Criar dashboard com indicadores de atendimento;
- Implementar classificação por prioridade e SLA;
- Adicionar base de conhecimento pesquisável;
- Criar testes simulados de troubleshooting.
