# ⚡ Fonte Regulada Super Choke

Projeto de uma fonte de tensão regulada com saídas fixas e ajustáveis, utilizando os reguladores **LM7805** e **LM317**. Desenvolvido com esquemático, layout de PCI e visualização 3D no KiCad, além da montagem real da placa.

---

## 🔧 Componentes Principais

- LM7805 – Tensão fixa +5V
- LM317 – Tensão ajustável (1.25V até 12V)
- Diodos 1N5408 (retificação)
- Capacitores eletrolíticos (2200µF, 1000µF, 470µF)
- LED indicador
- Dissipadores de calor
- Conectores de entrada e saída (borne parafuso)

---

## 🛠️ Recursos do Projeto

- Entrada AC via transformador (conector de três pinos)
- Retificação com diodos de potência
- Regulagem linear com dissipação térmica
- Saída dupla:
  - 🔹 +5V fixa com LM7805
  - 🔹 +VREG ajustável com LM317
- Proteção com diodos de retorno e capacitores de filtragem
- LED indicador de funcionamento

---

## 🧠 Tecnologias Utilizadas

- **KiCad** para esquemático, layout e visualização 3D
- Projeto de trilhas e footprint manual
- Simulação elétrica básica e revisão de malha GND
- Projeto pronto para produção da PCI

---

## 📐 Esquemático

![Imagem do WhatsApp de 2025-07-15 à(s) 12 47 32_3267ac37](https://github.com/user-attachments/assets/47230c08-9f4a-4d76-9bec-464af0c8be8d)

---

## 🔵 Layout da Placa (PCI)

![Imagem do WhatsApp de 2025-07-15 à(s) 12 47 58_3ba06151](https://github.com/user-attachments/assets/a9bbf275-bcb4-4c59-96eb-e038d08f1213)

---

## 🟢 Visualização 3D

<img width="1068" height="602" alt="Fonte Regulada" src="https://github.com/user-attachments/assets/55608c6b-7230-412f-aac7-ef2c803c2a8a" />

---

## 📸 Placa Real Montada

Foto da versão física da fonte regulada montada e testada com sucesso:

![Imagem do WhatsApp de 2025-07-15 à(s) 12 58 39_d19d5c7c](https://github.com/user-attachments/assets/827ce4b7-32de-4561-aa28-0ae7b686dbdf)

> *Projeto 100% funcional, ideal para bancadas e testes com sistemas embarcados.*

---

## ⚙️ Aplicações

- Fontes de bancada para testes
- Projetos com microcontroladores (ESP32, Arduino, etc.)
- Prototipagem eletrônica
- Aplicações educacionais

---

## 👨‍💻 Autor

**Gabriel Barbosa Fernandes de Oliveira**  
Estudante de Engenharia de Computação – PUCPR  
🔗 [LinkedIn](https://www.linkedin.com/in/gabrielengcomp/)
