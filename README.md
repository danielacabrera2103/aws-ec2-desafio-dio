# ☁️ Desafio DIO: Gerenciamento de Instâncias EC2 na AWS

Este repositório foi criado como parte do desafio da DIO sobre **Gerenciamento de Instâncias EC2 na AWS**.  
O objetivo é documentar o processo de criação, configuração e gerenciamento de uma instância EC2 na nuvem da Amazon.

---

## 🧠 Objetivos de Aprendizagem

- Aplicar os conceitos de computação em nuvem com a AWS EC2;
- Criar e gerenciar instâncias virtuais;
- Documentar processos técnicos de forma clara e estruturada;
- Utilizar o **GitHub** para versionamento e compartilhamento de documentação técnica.

---

## 🛠️ Etapas Realizadas

1. **Criação da conta AWS**
   - Configuração inicial e verificação de identidade.
   - Acesso ao console AWS.

2. **Criação da Instância EC2**
   - Escolha da AMI (Amazon Machine Image): *Amazon Linux 2*.
   - Tipo de instância: `t2.micro` (elegível ao Free Tier).
   - Configuração de chave SSH para acesso seguro.
   - Definição de regras de segurança (Security Group).

3. **Acesso à Instância**
   - Conexão via **SSH** (Terminal/Linux) ou **EC2 Instance Connect**.
   - Teste de conectividade e comandos básicos.

4. **Personalização**
   - Instalação de pacotes via `yum update` e `yum install`.
   - Configuração de um pequeno servidor web (ex: Apache ou Nginx).

5. **Finalização**
   - Teste de acesso via navegador (`http://<IP-PÚBLICO>`).
   - Encerramento ou parada da instância para evitar custos extras.

---

## 📸 Capturas de Tela

As imagens estão na pasta [`/images`](./images):

- `ec2-dashboard.png` – Instância criada e rodando;
- `ssh-connection.png` – Conexão via terminal;
- `apache-running.png` – Servidor web funcionando.

---

## 💡 Insights e Aprendizados

- Compreendi melhor a importância das **chaves de segurança (Key Pairs)**.
- Aprendi a configurar **grupos de segurança** para controlar o tráfego de rede.
- Notei como é simples e poderoso gerenciar servidores via AWS Management Console.
- Entendi o custo-benefício do **Free Tier** e boas práticas para evitar cobranças.

---

## 🧩 Recursos Utilizados

- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [AWS Free Tier](https://aws.amazon.com/free)
- [DIO – Formação Cloud Practitioner](https://www.dio.me/)
- Terminal (Linux/Mac) ou PowerShell (Windows)

---

## 👨‍💻 Feito Por:

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://hermes.dio.me/users/student/d1b13e0b-cac7-46af-b99f-f09d892c8215.jpg"
    />
    <p>&nbsp&nbsp&nbsp Daniela Cabrera<br>
    &nbsp&nbsp&nbsp
    <a 
        href="https://github.com/danielacabrera2103">
        GitHub
    </a>
    &nbsp;|&nbsp;
    <a 
        href="https://www.linkedin.com/in/danielacabrerabr">
        LinkedIn
    </a>
    &nbsp;|&nbsp;
   
</p>
