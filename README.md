# Precifica ML — versão inicial funcional

Aplicativo web responsivo/PWA para celular Android e navegador.

## Recursos
- Calculadora com custo do produto, preço, comissão, tarifa fixa, frete, embalagem/outros, publicidade e impostos.
- Comparação de lucro e margem entre anúncios Clássico e Premium.
- Cálculo de preço mínimo estimado e preço para atingir lucro desejado.
- Catálogo local de produtos.
- Histórico local de simulações.
- Exportação CSV e backup/restauração JSON.
- Interface instalável como PWA em hospedagem HTTPS compatível.

## Como testar no computador
Abra `index.html` em um navegador moderno. A calculadora funciona localmente; para testar instalação PWA e modo offline, hospede por HTTPS (ou use servidor local).

## Como disponibilizar na internet
1. Crie uma conta no GitHub e um repositório público chamado `precifica-ml`.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Abra Settings → Pages, escolha publicar a partir da branch `main` e pasta `/ (root)`.
4. Aguarde o link do GitHub Pages e abra-o no Android pelo Chrome.
5. No Chrome, menu ⋮ → “Instalar app” ou “Adicionar à tela inicial”.
   Alternativa: hospedar a pasta num serviço de hospedagem estática HTTPS, como Netlify.

## Importante
- As taxas padrão são exemplos editáveis, não uma tabela oficial do Mercado Livre.
- O app não está conectado à sua conta do Mercado Livre nem consulta tarifas em tempo real.
- Os dados são salvos no armazenamento local do navegador/dispositivo. Limpar os dados do navegador pode apagá-los; use o backup JSON e exportações CSV.
- O projeto ainda não é um APK publicado na Play Store. A PWA pode ser instalada pelo navegador Android. Para publicar na Play Store, será necessário empacotar/testar o app e cumprir as exigências atuais do Google Play.
- Verifique comissão, tarifa fixa, frete, impostos e regras de categoria na sua conta antes de decidir o preço.
