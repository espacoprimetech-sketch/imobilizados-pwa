# Controle de Imobilizados 2118 – PWA

Sistema PWA para inventário de ativo imobilizado, substituto do Formulário 2118.

## Funcionalidades
- 📊 Dashboard com progresso por CC
- 🏭 Lista de ativos com filtros e busca
- 📷 Leitura de plaquetas (código de barras via câmera)
- 📍 Gestão de Centros de Custo com descrição completa
- 💰 Coluna de valores contábeis
- 📋 Relatório por CC com cabeçalho idêntico à planilha 2118
- ✍️ Assinatura digital do Responsável Controladoria
- 📊 Exportar CSV por CC
- 💾 Funciona offline (PWA)

## Deploy GitHub Pages (< 5 min)

```bash
cd imobilizados-pwa
git init
git add .
git commit -m "feat: PWA Controle Imobilizados 2118"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/imobilizados-pwa.git
git push -u origin main
```

Após o push:
1. Vá em **Settings → Pages**
2. Source: **Deploy from branch → main → / (root)**
3. Salvar → em ~2 min estará em: `https://SEU-USUARIO.github.io/imobilizados-pwa/`

## Uso
1. Acesse a URL do GitHub Pages pelo celular
2. Chrome → "Adicionar à tela inicial" para instalar como app
3. Clique em "Importar → Carregar Dados da Planilha 2118"
4. Use 📷 para ler plaquetas com código de barras
5. Relatório → selecione CC → assine → Gerar & Imprimir
