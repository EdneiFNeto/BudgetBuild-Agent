# 🏗️ **BudgetBuild — Sistema de Orçamentos para Casa de Material de Construção**

## 📘 **Visão Geral**

O **BudgetBuild** é um software especializado para geração, gestão e acompanhamento de orçamentos em lojas de materiais de construção.
Agora ele conta com:

- **Geração de link de pagamento online**
- **Agendamento de entrega direto no orçamento aprovado**

Isso transforma o orçamento em uma experiência completa de compra, desde a cotação até o pagamento e entrega.

---

# ⚙️ **Funcionalidades**

## **1. Catálogo de Produtos**

Cadastro completo com:

- Nome
- Código
- Preço
- Foto
- Estoque
- Categoria
- Descrição técnica

---

## **2. Geração de Orçamentos Inteligentes**

- Busca rápida por produtos
- Aplicação de desconto (por item ou geral)
- Cálculo de frete automático
- Impressão e envio via WhatsApp, e-mail ou link

---

## **3. 💳 Geração de Link de Pagamento**

Após finalizar um orçamento, o vendedor pode clicar em **“Gerar Link de Pagamento”**.

### O sistema então:

- Envia o valor total para o gateway (Mercado Pago, PagSeguro, Pix, Stripe etc.)
- Gera automaticamente um link único e seguro
- Permite ao cliente pagar por:

  - **Pix**
  - **Cartão de crédito**
  - **Boleto**
  - **Carteiras digitais**

### Benefícios:

- Agiliza a conversão do orçamento em venda
- Evita erros ao passar valores manualmente
- Permite vendas 100% remotas
- Facilita cobrança de sinal ou pagamento total

O link aparece dentro do orçamento e também pode ser enviado pelo vendedor.

---

## **4. 🗓️ Agendamento de Entrega**

Após o pagamento ser confirmado no sistema:

1. O vendedor acessa o orçamento aprovado
2. Clica em **“Agendar Entrega”**
3. Preenche:

   - Data da entrega
   - Horário preferencial
   - Endereço de entrega
   - Observações (local de descarga, referência, restrição de horário etc.)

### O cliente também pode:

- Confirmar o agendamento via link
- Receber notificação por WhatsApp ou e-mail

### Integrações possíveis:

- Sistema de rotas da loja
- Controle de carga do caminhão
- Impressão da ordem de entrega

---

## **5. Finalização do Processo**

O fluxo completo fica assim:

```
Selecionar produtos → Gerar orçamento → Enviar orçamento →
Cliente aprova → Gerar link de pagamento → Pagamento confirmado →
Agendar entrega → Entrega realizada
```

---

# 🧾 **Lista de Produtos (Para Simulação de Orçamentos)**

Abaixo segue a lista completa (mantida e organizada) para demonstrações:

---

## 🧱 **Cimento, Argamassa e Rejunte**

| Código | Produto                              | Unidade | Preço (R$) |
| ------ | ------------------------------------ | ------- | ---------- |
| CIM01  | Cimento CP-II 50kg                   | Saco    | 38,90      |
| CIM02  | Cimento CP-V ARI 50kg                | Saco    | 42,50      |
| ARG01  | Argamassa AC-I Interna 20kg          | Saco    | 16,90      |
| ARG02  | Argamassa AC-II Interna/Externa 20kg | Saco    | 18,50      |
| ARG03  | Argamassa AC-III Porcelanato 20kg    | Saco    | 28,90      |
| REJ01  | Rejunte Acrílico Branco 1kg          | Saco    | 8,90       |
| REJ02  | Rejunte Cinza 1kg                    | Saco    | 7,90       |

---

## 🧱 **Areia, Pedra e Insumos**

| Código | Produto            | Unidade | Preço (R$) |
| ------ | ------------------ | ------- | ---------- |
| ARE01  | Areia Média Lavada | m³      | 129,00     |
| ARE02  | Areia Fina Lavada  | m³      | 139,00     |
| PED01  | Pedra Brita 1      | m³      | 160,00     |
| PED02  | Pedra Brita 0      | m³      | 165,00     |
| CAL01  | Cal Hidratada 20kg | Saco    | 14,50      |

---

## 🪚 **Madeira e Derivados**

| Código | Produto                       | Unidade | Preço (R$) |
| ------ | ----------------------------- | ------- | ---------- |
| MAD01  | Caibro Eucalipto 5x5cm x 3m   | Peça    | 18,90      |
| MAD02  | Tábua Pinus 2,5cm x 20cm x 3m | Peça    | 31,00      |
| MAD03  | Sarrafo 2x3cm x 3m            | Peça    | 7,50       |
| MAD04  | Compensado 10mm 1,22 x 2,44m  | Placa   | 89,00      |

---

## 💧 **Material Hidráulico**

| Código | Produto                  | Unidade | Preço (R$) |
| ------ | ------------------------ | ------- | ---------- |
| HID01  | Tubo PVC 50mm 3m         | Barra   | 27,90      |
| HID02  | Tubo PVC 75mm 3m         | Barra   | 39,90      |
| HID03  | Joelho 90° PVC 50mm      | Peça    | 3,20       |
| HID04  | Joelho 90° PVC 75mm      | Peça    | 4,80       |
| HID05  | Registro de Esfera 1/2"  | Peça    | 14,50      |
| HID06  | Torneira PVC Jardim 1/2" | Peça    | 9,90       |

---

## ⚡ **Material Elétrico**

| Código | Produto                    | Unidade | Preço (R$) |
| ------ | -------------------------- | ------- | ---------- |
| ELE01  | Cabo Flexível 1,5mm (100m) | Rolo    | 145,00     |
| ELE02  | Cabo Flexível 2,5mm (100m) | Rolo    | 165,00     |
| ELE03  | Tomada 10A Branca          | Peça    | 7,50       |
| ELE04  | Interruptor Simples        | Peça    | 8,90       |
| ELE05  | Lâmpada LED 9W Bulbo       | Peça    | 11,90      |
| ELE06  | Disjuntor 20A Curva C      | Peça    | 23,00      |

---

## 🧰 **Ferramentas**

| Código | Produto               | Unidade | Preço (R$) |
| ------ | --------------------- | ------- | ---------- |
| FER01  | Martelo de Unha 27mm  | Peça    | 32,90      |
| FER02  | Trena 5m Aço          | Peça    | 24,00      |
| FER03  | Chave de Fenda 5mm    | Peça    | 8,90       |
| FER04  | Chave Phillips 3mm    | Peça    | 9,50       |
| FER05  | Alicate Universal 8"  | Peça    | 29,90      |
| FER06  | Desempenadeira de Aço | Peça    | 18,90      |

---

## 🚪 **Portas, Janelas e Acabamentos**

| Código | Produto                    | Unidade | Preço (R$) |
| ------ | -------------------------- | ------- | ---------- |
| ACAB01 | Porta Lisa de Madeira 80cm | Peça    | 199,00     |
| ACAB02 | Basculante Alumínio 60x40  | Peça    | 155,00     |
| ACAB03 | Fechadura Interna          | Peça    | 32,00      |
| ACAB04 | Puxador Inox 30cm          | Peça    | 45,00      |
| ACAB05 | Rodapé PVC 10cm (2m)       | Peça    | 24,00      |

---

## 🧱 **Pisos e Revestimentos**

| Código | Produto                     | Unidade | Preço (R$) |
| ------ | --------------------------- | ------- | ---------- |
| PISO01 | Piso Cerâmico Branco 45×45  | m²      | 29,90      |
| PISO02 | Porcelanato Acetinado 60×60 | m²      | 59,90      |
| REV01  | Revestimento 30×60 Branco   | m²      | 34,90      |
| REV02  | Pastilha Resinada 30×30     | Placa   | 9,90       |

---

## 🎨 **Tintas e Acessórios**

| Código | Produto                   | Unidade | Preço (R$) |
| ------ | ------------------------- | ------- | ---------- |
| TIN01  | Tinta Acrílica 18L Branco | Galão   | 169,00     |
| TIN02  | Massa Corrida 20kg        | Balde   | 39,90      |
| TIN03  | Rolo de Pintura 23cm      | Peça    | 14,90      |
| TIN04  | Pincel 2"                 | Peça    | 7,90       |
| TIN05  | Solvente Aguarrás 900ml   | Frasco  | 10,90      |

---

## 🛡️ **EPI**

| Código | Produto               | Unidade | Preço (R$) |
| ------ | --------------------- | ------- | ---------- |
| EPI01  | Luva de Raspa         | Par     | 12,90      |
| EPI02  | Óculos de Proteção    | Peça    | 9,90       |
| EPI03  | Capacete de Segurança | Peça    | 24,00      |
| EPI04  | Bota PVC Cano Curto   | Par     | 39,90      |

---

# 🎉 **Tudo pronto para simular o processo completo**

O agente agora pode:

1. Escolher produtos
2. Criar orçamento
3. Aplicar descontos
4. Gerar PDF
5. Enviar orçamento ao cliente
6. Criar link de pagamento
7. Aguardar confirmação
8. Agendar entrega
9. Finalizar venda

---

# 📄 Modelo de Recibo Gerado pelo Software (NOVO)

Este é o modelo oficial do recibo utilizado no BudgetBuild:

Loja de Materiais ConstruBem
CNPJ: 12.345.678/0001-99
Telefone: (11) 99999-9999

---

RECIBO DE PAGAMENTO
Data: 27/11/2025 - 14:32
Número da Transação: MP-993821-A1

Cliente: João da Silva
CPF: 123.456.789-00

---

ITEMS
1x Cimento CP-II 50kg .................... R$ 38,90
4x Tubo PVC 50mm 3m ...................... R$ 111,60
2x Tomada 10A Branca ..................... R$ 15,00
1x Martelo de Unha 27mm .................. R$ 32,90

Subtotal: R$ 198,40
Desconto: R$ 10,00
Frete: R$ 20,00

TOTAL PAGO: R$ 208,40
Forma de Pagamento: Pix (Link de Pagamento)
Pagamento Confirmado: SIM

---

Agradecemos pela sua compra!
Sua entrega será agendada pelo setor de logística.

ConstruBem — Qualidade para sua obra.
