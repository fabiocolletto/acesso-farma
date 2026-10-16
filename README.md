# Acesso ao Farma

Atalho estático para https://app.5horas.com.br/alfa/farma/. O redirecionamento ocorre no navegador,
na mesma aba, preservando consulta e fragmento e sem manipular autenticação.
Não é um redirecionamento HTTP 301/302. Sem JavaScript, o link permite continuar.
O destino é fixo; parâmetros recebidos não escolhem outro servidor.

Domínio: `farma.5horas.com.br`.
DNS previsto: CNAME `farma` → `fabiocolletto.github.io`.
Publicação: GitHub Pages, branch `main`, pasta `/`.
HTTPS precisa de DNS válido para emissão do certificado e posterior enforcement.
