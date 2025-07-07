# 🖥️ Máquina Virtual no Google Colab

Este projeto tem como objetivo a criação de uma **máquina virtual Linux com interface gráfica (GUI)** executada diretamente no ambiente do **Google Colab**, utilizando recursos gratuitos da Google Cloud. A proposta permite a simulação de um desktop remoto com suporte a automações, testes de scripts e uso gráfico de ferramentas, sem necessidade de instalação local.

---

## 🚀 Funcionalidades

- ✅ Ambiente gráfico XFCE acessível via RDP
- ✅ Instalação automatizada de dependências via Shell Script
- ✅ Compatibilidade com Selenium, PyAutoGUI, Firefox e x11vnc
- ✅ Acesso remoto via [Cloudflare] (túnel público)
- ✅ Interface para upload/download de arquivos
- ✅ Execução temporária e leve diretamente no navegador

---

## 🧠 Aplicações

- Testes de **automação web** com interface gráfica
- Simulações e **demonstrações de scripts com interface visual**
- Execução de **bots com Selenium ou PyAutoGUI**
- Desenvolvimento em ambientes sem recursos locais
- Ensino e apresentações interativas de sistemas gráficos

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta        | Função                                           |
|-------------------|--------------------------------------------------|
| Google Colab      | Execução de notebooks Python na nuvem           |
| Ubuntu XFCE       | Ambiente gráfico leve e funcional               |
| xRDP / x11vnc     | Acesso remoto via protocolo gráfico             |
| Firefox           | Navegador para testes gráficos                  |
| Ngrok             | Túnel para acesso externo                       |
| Selenium          | Automação de navegação web                      |
| PyAutoGUI         | Controle do mouse e teclado                     |
| Python 3 / Shell  | Lógica de execução e instalação automática      |

---

## 📦 Como usar

1. Acesse o notebook do projeto:  
   👉 [Clique aqui para abrir no Colab](https://github.com/marcosengdados/Maquina_virtual_colab/blob/main/maquina_virtual_colab.ipynb)

2. Siga as instruções passo a passo:
   - Instale os pacotes
   - Autentique o Ngrok
   - Inicie a interface gráfica

3. Acesse o endereço RDP fornecido com login e senha padrão (`colab`/`colab123` por padrão, modificável no script).

---

## ⚠️ Observações

- O ambiente é **temporário**, durando enquanto a sessão do Colab estiver ativa.
- O uso prolongado pode estar sujeito a limites de tempo da Google.
- Para conexões externas, é necessário um token do Ngrok (gratuito).

---

## 🤝 Contribuição

Sinta-se à vontade para **forkar**, **sugerir melhorias**, **reportar issues** ou adaptar para outros usos. Este projeto é **open-source** e foi pensado para facilitar o acesso a ambientes gráficos em nuvem.

---

## 📄 Licença

Este projeto está licenciado sob os termos da [MIT License](LICENSE).

---

## 🌐 Autor

Desenvolvido por [Marcos Vinicius Lima](https://www.linkedin.com/in/marcosdados/)  
🔗 Repositório: [github.com/marcosengdados/Maquina_virtual_colab](https://github.com/marcosengdados/Maquina_virtual_colab)


