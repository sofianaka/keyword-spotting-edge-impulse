
# 🎙️ Reconhecimento de Palavras-Chave (Keyword Spotting)

## 📌 Descrição

Este projeto foi desenvolvido para a disciplina de Computação na Borda e IA Aplicada a Sistemas Embarcados, utilizando a plataforma Edge Impulse.

O objetivo é reconhecer comandos de voz em português:

* liga
* desliga
* sobe
* desce

## 🧠 Tecnologias utilizadas

* Edge Impulse
* MFCC (processamento de áudio)
* Redes neurais (Conv1D)
* IA embarcada (Edge AI)

## 📊 Dataset

* 300 amostras
* 6 classes
* Frequência: 16kHz
* Split: 80% treino / 20% teste

## 📈 Resultados

* Acurácia de validação: 46.2%
* Problemas observados:

  * Confusão entre "liga" e "desliga"
  * Sensibilidade a ruídos
  * Baixa confiança na live classification

## ⚠️ Limitações

* Dataset pequeno
* Pouca diversidade de vozes
* Similaridade fonética entre classes

## 🚀 Melhorias futuras

* Aumentar o dataset
* Aplicar data augmentation
* Melhorar arquitetura do modelo
* Ajustar threshold de confiança

## 🔗 Projeto no Edge Impulse

[Acessar projeto no Edge Impulse](https://studio.edgeimpulse.com/public/948415/live)




