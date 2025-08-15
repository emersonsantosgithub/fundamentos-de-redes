# 🛡️ Máscara de Rede

A **máscara de rede** (ou **subnet mask**) é uma sequência de bits que define como o **endereço IP** será dividido em duas partes: **rede** e **host (dispositivo)**.  
Ela determina quantos bits são usados para identificar a rede e quantos são usados para identificar o host.

---

## 📌 Um endereço IP tem duas partes:

1. **Parte da rede:** identifica a rede à qual o host pertence.  
2. **Parte do host:** identifica o host dentro dessa rede.

---

A máscara de rede é representada como uma sequência decimal de 4 grupos divida por pontos, semelhante ao IP.  
Ela utiliza **bits 1 contínuos** para a rede e **bits 0 contínuos** para os hosts.  

**Exemplo:**

- IP: `192.168.1.10` → em binário: `11000000.10101000.00000001.00001010`  
- Máscara: `255.255.255.0` → em binário: `11111111.11111111.11111111.00000000`  

Neste exemplo, os **24 primeiros bits** são dedicados à rede e os **8 bits restantes** aos hosts.

---

💡 **Resumo rápido:**

1. A máscara de rede define o **tamanho da rede** e quantos dispositivos podem existir dentro dela.  
2. É essencial para que os **roteadores saibam para onde enviar os pacotes** na rede.
