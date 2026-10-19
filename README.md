# Conversor de paletes

Converte caixas e unidades soltas em paletes, lastros, pacotes e unidades restantes,
de acordo com a configuração de cada produto.

## Como usar
Abra o `index.html` no navegador (computador ou celular).

1. Escolha o produto.
2. Informe a quantidade de caixas e de unidades soltas.
3. O resultado aparece na hora.

## Configuração do produto
- **Unidades por pacote**
- **Pacotes por lastro** (quantos pacotes formam uma camada)
- **Lastros por palete** (quantas camadas formam um palete)

### Produtos já cadastrados
| Produto | Un/pacote | Pacotes/lastro | Lastros/palete | Pacotes/palete |
|---|---|---|---|---|
| Lata 350ml | 12 | 22 | 14 | 308 |
| Garrafa 600ml | 24 | 7 | 7 | 49 |
| Garrafa 1000ml | 12 | 10 | 6 | 60 |
| Lata 269ml | 12 | 28 | 14 | 392 |
| Long neck 275ml | 12 | 28 | 8 | 224 |
| Garrafa 300ml | 12 | 8 | 9 | 72 |

Para alterar um produto, salve de novo com o mesmo nome.
Os produtos ficam salvos no navegador de cada aparelho.

## Cálculo
1. Total de unidades = caixas × unidades por pacote + unidades soltas
2. Pacotes = total ÷ unidades por pacote (o resto são as unidades soltas)
3. Paletes = pacotes ÷ (pacotes por lastro × lastros por palete)
4. O que sobra vira lastros completos e depois pacotes avulsos
