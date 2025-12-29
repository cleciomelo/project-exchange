# Ocultar endereço de e-mail no catálogo global do Exchange On-premise
Ocultar listas de endereços (Address Lists ou GAL – Global Address List) em um ambiente On-Premise (Exchange Server). Isso é comum quando não se deseja que determinados grupos ou listas fiquem visíveis para todos os usuários no Outlook ou OWA.

## 🚀 Check List 
Com acesso de Administrador no Servidor * **(AD)**, abra o Gerenciador do Servidor e clique em * **Usuário e Computadores do Activce Directory**.

<img width="567" height="302" alt="image" src="https://github.com/user-attachments/assets/edfb61d1-f302-4c27-b94b-dd56ae59f964" />

Clique na aba Objeto para identificar OU (Unidade Organizacional) nesse exemplo a OU do usuário é * **DT**

<img width="878" height="547" alt="image" src="https://github.com/user-attachments/assets/aeda8892-2f8d-458e-8d0e-541de6b37f3c" />

Nas pastas laterais na esquerda, em SCR expandir a OU DT, dentro da pasta Intermediário com duplo clique no usuário, depois clique na aba * **Editor de Atributos**  
Procure pelo atributo por nome * **msExchHideFromAddressLists** e defina como Verdadeiro * **(TRUE)**.

<img width="1024" height="537" alt="image" src="https://github.com/user-attachments/assets/172522e1-3534-4a2e-a75a-74bfd41229f8" />


* **Depois clique em Aplicar para salvar**.


<img width="427" height="567" alt="image" src="https://github.com/user-attachments/assets/9b55407d-10c0-4c28-9a0c-bde2ba6db66f" />

## 🛠️ Aplicação
Windows Server 2012 R2

## ✒️ Autor
* **Analista de TI** 
* **Clécio Melo** 


