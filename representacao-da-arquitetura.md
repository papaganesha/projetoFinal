# Representação da Arquitetura

## Modelo de Arquitetura
![](.gitbook/assets/arquitetura.PNG)

### Fluxos
- Usuario interage com React Native.
- Ação do Usuário causa uma chamada para a API do Node ou do Cometchat.
- Caso a chamada tenho sido para a API do Cometchat, ela ira receber as mensagens que estão armazenadas para o usuário e seus Matchs.
- Caso chamada tenha sido para API Node, ela identifica o pedido e processa oque foi requisitado.
- Caso a API Node precise armazenar uma foto ela irá se comunicar com o Cloudinary.
- Caso a API Node precise buscar, alterar ou excluir dados da base de dados ela irá se comunicar com o MongoDB.

## Visão Lógica

## Requisitos, Casos de Uso, Regras de Negócio
<a href="https://docs.google.com/document/d/19oKj4Zr_HFHgyRyFSSqEWiRJWSP0U0Mtd7cCmj3HGtw/edit?usp=sharing" title="Documento de Requisitos, Regras de Negócios e Casos de Uso"><img src="https://gdm-catalog-fmapi-prod.imgix.net/ProductLogo/23b998d3-f991-4f01-821a-e2f902f884d7.png?auto=format&q=30&w=30&h=90&fit=max&dpr=3" ></a>

### Banco de Dados -- Esquema Json
![](.gitbook/assets/userSchema.PNG)

