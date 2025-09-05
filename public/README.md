# Pasta Public - Assets da Apresentação

## Logo da Empresa

Para adicionar sua logo à apresentação:

### 1. Arquivo da Logo
- **Nome do arquivo**: `logo-placeholder.png` (ou mantenha este nome)
- **Tamanho recomendado**: 120x40 pixels
- **Formatos aceitos**: PNG, SVG, JPG
- **Fundo**: Preferencialmente transparente (PNG ou SVG)

### 2. Como adicionar
1. Coloque o arquivo da sua logo nesta pasta (`public/`)
2. Renomeie para `logo-placeholder.png` ou atualize o caminho no HTML
3. A logo será exibida automaticamente no cabeçalho da apresentação

### 3. Personalização
Se quiser usar um nome diferente para o arquivo:
1. Abra o arquivo `apresentacao.html`
2. Procure por `src="public/logo-placeholder.png"`
3. Substitua pelo nome do seu arquivo

### 4. Fallback
Se a imagem não for encontrada, será exibido o texto "[SUA LOGO AQUI]" como placeholder.

---

**Dica**: Para melhor qualidade, use arquivos SVG quando possível, pois são vetoriais e ficam nítidos em qualquer tamanho.