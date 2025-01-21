# Phishing para captura de senhas do Facebook
Nota: Esse é um Desafio da Dio.me, utilizado para fins educacionais
### Ferramentas

-Kali Linux (https://www.kali.org/)
-Setoolkit (Ferramenta já instala no Kali Linux)

### Passo-a-passo para configurar o phishing no Kali Linux

- Primeiramente teremos que ter acesso root usando comando: ``` sudo su ``` e logo após, digitamos a senha da nossa maquina:
  ![sudosusenha](https://github.com/user-attachments/assets/11954fb0-4d6b-470e-9c94-2f2981e0b6f6)

- Iniciando o setoolkit: ``` setoolkit ```
- ![setoolkit](https://github.com/user-attachments/assets/56fa3fbd-0567-4324-9b73-00b9f05cb1f1)

- Após usar o comando setoolkit apareça muitas informaçôes, role ate em baixo apara achar o menu "Select from the menu", a seleçao funciona digitando o numero da opçao que deseja
  
- Começaremos com a opçao 1: Tipo de ataque: ``` Social-Engineering Attacks ```
   ![menu1](https://github.com/user-attachments/assets/c398840c-522b-49d1-be00-eede6c1149c6)

- Opção 2: Vetor de ataque: ``` Web Site Attack Vectors ```
   ![menu2](https://github.com/user-attachments/assets/27195cc3-e50c-4562-a2d7-9e14c622ff96)

- Opção 3: Método de ataque: ```Credential Harvester Attack Method ```
   ![menu3](https://github.com/user-attachments/assets/7a57338c-4617-4f67-836f-16a57e98c431)

- Opção 4: Método de ataque: ``` Site Cloner ```
   ![menu4](https://github.com/user-attachments/assets/7b1f7ba2-d629-4ecf-a3fe-66dee47c105a)
  
- Após ter escolhido as opções vai aparecer uma mensagem dizendo que irá hospedar o template falso no ip da maquina, basta apertar ENTER
  
   ![menu5ip](https://github.com/user-attachments/assets/26ffcfd0-a01e-44e6-bdc5-0e928da8a8c1)

- Ele pedirá para voce inserir uma link para a template falso, pode ser o facebbok ou instagram URL para clone: http://www.facebook.com
  
  ![menu6https](https://github.com/user-attachments/assets/c9c9f1d5-c280-4edb-af2e-8c113c2292bf)

- Após terminado, aparecerá essa mensagem e esta pronto, basta ir no navegador e digitar o Ip da sua VM. Para obter o endereço da máquina: ifconfig
  
  ![final](https://github.com/user-attachments/assets/027939e2-fed5-4336-81f6-4389e598d3db)

### Resutados
- Se tudo ocorrer corretamente, ao digitar o email e a senha, vai aparecer no seu prompt de comando igual a imagem abaixo demonstra
  
  ![Alt text](./passwd.png "Optional title")

- O processo funciona tambem para o instagram, basta mudar o link de clonagem

- Visão da pessoa que digita seu acesso no instagram:
  
  ![instalogin](https://github.com/user-attachments/assets/19710169-f27b-4494-83c8-e89187472132)

- A informaçao da login no seu prompt
  
  ![concluido2](https://github.com/user-attachments/assets/f06db0ad-abdc-4abd-ac37-5f64db669ca7)

  
