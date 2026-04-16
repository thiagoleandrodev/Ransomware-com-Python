# Ransomware-com-Python

🔐 File Encryption Simulator (Python)

Simulação educacional de criptografia de arquivos, desenvolvida em Python para demonstrar conceitos fundamentais de segurança da informação.

🚀 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de explorar, na prática, como funciona o processo de criptografia e descriptografia de arquivos.

A aplicação simula o comportamento de softwares que protegem dados sensíveis, permitindo compreender como arquivos podem ser transformados e recuperados por meio de uma chave.

💡 O foco está no aprendizado técnico e na aplicação de boas práticas — sem qualquer uso malicioso.

🧠 O que eu aprendi

Durante o desenvolvimento deste projeto, trabalhei com:

Implementação de criptografia simétrica
Manipulação de arquivos em Python
Organização de código em scripts independentes
Estruturação de projetos para o GitHub
Escrita de documentação técnica clara
🗂️ Estrutura do Projeto
📁 file-encryption-simulator/
│
├── encrypter.py   # Criptografa arquivos
├── decrypter.py   # Restaura arquivos criptografados
├── README.md      # Documentação do projeto
└── /images        # (Opcional) Demonstrações visuais
⚙️ Como Funciona

O fluxo do sistema é simples e direto:

graph TD
A[Arquivo original] --> B[Encrypter]
B --> C[Arquivo criptografado]
C --> D[Decrypter]
D --> E[Arquivo restaurado]

🔐 Criptografia
Lê o conteúdo de um arquivo
Aplica transformação baseada em chave
Gera versão criptografada

🔓 Descriptografia
Lê o arquivo criptografado
Aplica a chave correta
Restaura o conteúdo original

▶️ Como Executar
Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Execute a criptografia
python encrypter.py
Execute a descriptografia
python decrypter.py

🛠️ Tecnologias Utilizadas
Python 3
Manipulação de arquivos (I/O)
Conceitos básicos de criptografia

📸 Demonstração
/images/encryption-example.png
/images/decryption-example.png

⚠️ Aviso
Este projeto foi desenvolvido exclusivamente para fins educacionais.
Não deve ser utilizado para qualquer atividade que comprometa a segurança de sistemas ou dados de terceiros.

🚀 Melhorias Futuras
Interface gráfica (GUI)
Suporte a múltiplos arquivos
Integração com bibliotecas como cryptography
Geração segura de chaves
Logs de execução

🌐 Deploy / Repositório
👉 https://github.com/thiagoleandrodev

👨‍💻 Autor
Desenvolvido por você ✨
https://www.linkedin.com/in/thiago-dev26/
