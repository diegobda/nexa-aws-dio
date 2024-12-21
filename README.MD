# 🎨 AWS Rekognition Celebrity Recognition Project

## 👨‍💻 Desenvolvido por Diego dos Santos Gonçalves

Este projeto utiliza o serviço AWS Rekognition para reconhecer celebridades em imagens e destacar seus rostos com caixas delimitadoras. Ele é ideal para aprendizado ou aplicações que envolvam detecção de celebridades com visualizações personalizadas.

---

## 📋 Funcionalidades
- Detecta celebridades em imagens.
- Desenha caixas vermelhas em torno dos rostos reconhecidos.
- Adiciona o nome das celebridades com fundo destacado.
- Gera uma nova imagem processada para cada imagem de entrada.

---

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **AWS Rekognition**: Serviço de Machine Learning para reconhecimento de celebridades.
- **Pillow (PIL)**: Manipulação de imagens.

---

## 📦 Dependências

Certifique-se de que as bibliotecas abaixo estão instaladas no seu ambiente:

1. **boto3**: Biblioteca para interagir com os serviços AWS.
   ```bash
   pip install boto3
   ```
2. **mypy-boto3-rekognition**: Tipagem para o serviço AWS Rekognition.
   ```bash
   pip install mypy-boto3-rekognition
   ```
3. **Pillow**: Biblioteca para manipulação de imagens.
   ```bash
   pip install pillow
   ```

---

ou 
pip install boto3 mypy-boto3-rekognition pillow





## 📁 Estrutura de Diretórios
```plaintext
project/
├── images/             # Pasta para imagens de entrada e saída
├── main.py             # Script principal
├── requirements.txt    # Lista de dependências
├── README.md           # Documentação do projeto
```

---

## 🚀 Passo a Passo

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/seu-usuario/aws-celebrity-recognition.git
   cd aws-celebrity-recognition
   ```

2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure suas credenciais AWS**:
   Configure suas credenciais no arquivo `~/.aws/credentials` ou use as variáveis de ambiente:
   ```plaintext
   [default]
   aws_access_key_id=SEU_ACCESS_KEY_ID
   aws_secret_access_key=SEU_SECRET_ACCESS_KEY
   region=SEU_REGION
   ```

4. **Adicione as imagens na pasta `images`**.

5. **Execute o script principal**:
   ```bash
   python main.py
   ```

6. **Confira as imagens processadas**:
   As imagens com caixas e nomes das celebridades serão salvas na pasta `images/` com o sufixo `-resultado` no nome.

---

## ✨ Exemplos de Uso

### 🎯 Entrada
Imagem original na pasta `images/`:
```
images/bbc.jpg
```

### 🖼️ Saída
Imagem processada salva como:
```
images/bbc-resultado.jpg
```

A imagem processada terá caixas delimitadoras e nomes das celebridades reconhecidas.

---

## 🌟 Contribuições
Fique à vontade para abrir issues ou enviar pull requests. Toda contribuição é bem-vinda! 😊

---

## ⚖️ Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

-

## 📞 Contato
Diego dos Santos Gonçalves  
✉️ E-mail: [diegodba9@gmail.com](mailto:diegodba9@gmail.com)  
💼 LinkedIn: [Seu Perfil](https://www.linkedin.com/in/diegolinkedin/details/certifications/l/)
