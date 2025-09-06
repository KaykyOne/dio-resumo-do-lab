# Um Resumo do que Aprendi

Neste capítulo do curso, aprofundei meu entendimento sobre os diferentes tipos de servidores e suas aplicações.  
Aprendi a diferenciar **servidores locais** e **em nuvem**, compreendendo suas características, vantagens e limitações. Além disso, explorei a distinção entre **servidores públicos e privados**, analisando aspectos como custos, segurança, escalabilidade e flexibilidade.

Também estudei o **modelo de servidor híbrido**, que combina elementos do ambiente local e da nuvem, oferecendo o equilíbrio ideal entre controle, eficiência operacional e otimização de recursos. Essa abordagem possibilita aproveitar o melhor de ambos os mundos, garantindo maior desempenho, segurança e economia de acordo com as necessidades da organização.

---

## Resumo sobre Computação em Nuvem 🌐

A computação em nuvem (ou *cloud computing*) é um modelo de uso de recursos de TI através da internet, sem precisar ter tudo instalado no computador ou servidor local. Em vez de comprar e manter infraestrutura própria, as empresas ou pessoas usam serviços que ficam disponíveis remotamente.

### Tipos principais de serviço:

- **IaaS (Infraestrutura como Serviço)**: aluguel de máquinas virtuais, armazenamento e rede.  
  *Ex.: AWS, Azure*  

- **PaaS (Plataforma como Serviço)**: fornece ferramentas prontas para desenvolver e hospedar aplicações, sem se preocupar com servidores.  
  *Ex.: Heroku*  

- **SaaS (Software como Serviço)**: softwares prontos acessados pela internet.  
  *Ex.: Google Drive, Office 365*  

### Principais benefícios:

- **Escalabilidade**: aumentar ou reduzir recursos conforme a necessidade.  
- **Custo**: paga-se apenas pelo que se usa, sem comprar hardware.  
- **Acesso remoto**: dá pra usar de qualquer lugar com internet.  
- **Confiabilidade**: provedores grandes garantem backup, segurança e alta disponibilidade.  

### Desafios:

- Dependência de terceiros.  
- Privacidade de dados.  
- Custos escondidos se não for bem gerenciado.

---

# Documentação Técnica do Desafio

## 1. Resumo

Neste desafio, configurei um ambiente no **Microsoft Azure**, aprendi a criar e gerenciar recursos na nuvem e documentei todo o processo técnico passo a passo.

---

## 2. Configuração do Ambiente no Microsoft Azure

### 2.1 Criação de Conta

- Criei uma conta no Microsoft Azure.  
- Ativei o plano gratuito (se aplicável).  
- Configurações iniciais de segurança: autenticação multifator e senha forte.

### 2.2 Criação de Recursos

- Criei recursos como **máquinas virtuais (VM)**, **bancos de dados** e **serviços web**.  
- Configurei **regiões**, **grupos de recursos** e **redes virtuais**.  

**Definições importantes:**  
- Tipo de máquina virtual  
- Sistema operacional  
- Tamanho e capacidade  

### 2.3 Configurações Adicionais

- Firewalls, regras de acesso e portas abertas  
- Configuração de backups automáticos  
- Monitoramento de recursos via Azure Monitor

---

## 3. Passo a Passo das Ações Realizadas

1. Acessar o portal do Azure: [https://portal.azure.com](https://portal.azure.com)  
2. Criar um grupo de recursos chamado `DesafioTecnico`  
3. Criar uma VM Linux chamada `ServidorDesafio`  
   - Sistema: Ubuntu 22.04  
   - Região: Brasil Sul  
   - Tamanho: B1s  
4. Configurar regras de firewall: liberar porta 22 para SSH  
5. Conectar à VM usando SSH e instalar softwares necessários  
6. Testar se a VM está acessível e funcionando corretamente  

> Dica: você pode adicionar prints de cada etapa usando:  
> `![Descrição](caminho/da/imagem.png)`

---

## 4. Dicas, Aprendizados e Problemas Encontrados

### Dicas
- Sempre nomeie recursos de forma clara para facilitar o gerenciamento.  
- Configure backups e alertas desde o início.  
- Documente cada passo durante a configuração para não esquecer nada.

### Aprendizados
- Como criar e gerenciar recursos no Azure  
- Diferença entre tipos de máquinas virtuais e serviços  
- Boas práticas de segurança na nuvem

### Problemas Encontrados e Soluções
- **Problema:** Não consegui conectar na VM via SSH  
  **Solução:** Verifiquei as regras de firewall e liberei a porta 22 corretamente

- **Problema:** Erro ao criar banco de dados  
  **Solução:** Ajustei a configuração de rede e permissões de acesso
