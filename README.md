<body>

  <h1>📋 Sistema de Gestão para Clínica Médica</h1>

  <h2>📁 Sobre o Projeto</h2>
  <p>Este é um sistema desktop para gerenciamento de uma clínica médica, desenvolvido em Python. A aplicação permite o cadastro e controle de pacientes, médicos e consultas, com uma interface gráfica amigável e persistência de dados via banco de dados SQLite.</p>

  <h2>🛠️ Funcionalidades</h2>
  <ul>
    <li><strong>Cadastro de Pacientes:</strong> Gerencie os dados dos pacientes.</li>
    <li><strong>Cadastro de Médicos:</strong> Controle das informações dos profissionais da clínica.</li>
    <li><strong>Consultas:</strong> Agendamento e listagem de consultas médicas.</li>
    <li><strong>Ajuda:</strong> Interface de suporte com instruções de uso.</li>
  </ul>

  <h2>🚀 Tecnologias Utilizadas</h2>
  <ul>
    <li>Python 3.12+</li>
    <li>SQLite (via <code>sqlite3</code>)</li>
    <li>PyQt5 (presumido)</li>
  </ul>

  <h2>📂 Estrutura do Projeto</h2>
  <pre><code>clinica.code/
│
├── main.py                # Arquivo principal para executar o sistema
├── db_manager.py          # Gerenciador de banco de dados SQLite
├── ui_paciente.py         # Interface gráfica para pacientes
├── ui_medico.py           # Interface gráfica para médicos
├── ui_consulta.py         # Interface gráfica para consultas
└── ui_ajuda.py            # Interface gráfica de ajuda
</code></pre>

  <h2>▶️ Como Executar</h2>
  <ol>
    <li>Certifique-se de ter o Python instalado (versão 3.12 ou superior).</li>
    <li>Instale as dependências necessárias:
      <pre><code>pip install pyqt5</code></pre>
    </li>
    <li>Execute o arquivo principal:
      <pre><code>python main.py</code></pre>
    </li>
  </ol>

  <h2>🧾 Licença</h2>
  <p>Este projeto é de uso didático e está disponível para modificações e estudos.</p>

</body>
