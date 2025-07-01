# CNN com Explicabilidade no CIFAR-10

Este projeto apresenta uma CNN simples treinada no dataset CIFAR-10, com múltiplas abordagens de explicabilidade visual aplicadas às classificações da rede.

## 🧠 Explicadores incluídos
- Gradiente simples
- SmoothGrad
- LRP (Z, Epsilon, AlphaBeta)
- NoiseTunnel

## 🖼️ Exemplo de visualização
![Exemplo de explicação](images/exemplo_1.png)
![Exemplo de explicação](images/exemplo_2.png)
![Exemplo de explicação](images/exemplo_3.png)
![Exemplo de explicação](images/exemplo_4.png)
![Exemplo de explicação](images/exemplo_5.png)

## 📚 Tecnologias
- PyTorch
- Matplotlib
- NumPy

## 🗂️ Organização
- `notebooks/`: notebook principal com modelo e explicabilidade
- `explainability/`: módulo com implementações dos métodos de explicação
- `images/`: imagens dos resultados explicativos

## ▶️ Como executar
1. Instale dependências:
```bash
pip install -r requirements.txt
```
2. Execute o notebook:
```bash
notebooks/Cifar10_Torch.ipynb
```

## 📈 Resultados
A combinação de explicadores oferece boas perspectivas visuais sobre o que a rede "vê" em diferentes categorias (avião, gato, carro, etc).

