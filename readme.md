# ✨ Classificação de Imagens de Frutas Utilizando HoG, SVM e CNN ✨

Olá! 👋 Bem-vinda(o) ao meu projeto de classificação de imagens de fruta! 🍌

## Sobre o Projeto 👩‍💻

Neste projeto, experimentei duas abordagens diferentes para a classificação de imagens de frutas. Primeiro, usei o Descritor de Gradientes Orientados Histograma (Histogram of Oriented Gradients - HoG) e Máquinas de Vetores de Suporte (Support Vector Machines - SVM). Na segunda abordagem, tentei usar uma Rede Neural Convolucional (Convolutional Neural Network - CNN), que é uma técnica popular de aprendizado profundo para classificação de imagens.

O conjunto de dados consiste em imagens de 5 categorias de frutas diferentes, cada uma contendo cerca de 1000 imagens. O objetivo era treinar os classificadores para distinguir entre estas 5 categorias diferentes.

## Como o Projeto Funciona? 🧠

Neste projeto, desenvolvi duas versões do classificador.

### Versão 1: HoG + SVM

1. **Preparação de Dados**: Primeiro, carreguei todas as imagens de frutas de diferentes pastas, onde cada pasta representa uma categoria de fruta. Cada imagem é redimensionada para um múltiplo de 8 e convertida em escala de cinza. 
2. **Extração de Características HoG**: Em seguida, para cada imagem, calculo o descritor HoG, que serve como um 'resumo' da imagem. Este descritor captura a estrutura básica e a aparência da imagem em um formato que é fácil para um algoritmo de aprendizado de máquina entender. 
3. **Treinamento do Classificador SVM**: Agora, com os descritores HoG prontos, utilizei um classificador SVM para 'aprender' a partir desses descritores. Com base neste aprendizado, o classificador será capaz de prever a categoria de novas imagens de frutas. 🎓
4. **Teste do Classificador**: Por fim, testo a precisão do classificador comparando suas previsões com as categorias verdadeiras das imagens de teste. Isso me dá uma medida de quão bem o classificador está funcionando.

A precisão obtida nesta primeira versão foi de aproximadamente 56% (não satisfatório).

### Versão 2: CNN

Na segunda versão, fizemos uso de uma Rede Neural Convolucional (CNN) para a classificação das imagens. A CNN aprende automaticamente e generaliza os padrões na imagem, o que nos permite pular a etapa de extração manual de características. No entanto, essa abordagem mostrou uma diminuição na acurácia, obtendo cerca de 43%.

## Conclusão 🌟

Embora os resultados com a CNN não tenham sido tão bons quanto com a combinação HoG + SVM, foi uma experiência de aprendizado valiosa. Compreender diferentes técnicas e como elas funcionam em diferentes situações nos dá uma visão mais aprofundada do desafiador campo do aprendizado de máquina e da visão computacional.

Vou continuar experimentando e otimizando meus modelos para obter melhores resultados. Se você tiver alguma sugestão, ficarei feliz em ouvir! Espero que você tenha achado este projeto interessante e informativo. 🚀
