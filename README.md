<div align="center">
  
  [![Pull request](https://img.shields.io/bitbucket/pr-raw/MarceloHarbs/P10Documentacao?style=social)](https://github.com/MarceloHarbs/P10Documentacao/pulls)
  [![GitHub commits](https://img.shields.io/github/last-commit/MarceloHarbs/P10Documentacao?style=social)](https://github.com/MarceloHarbs/P10Documentacao/commit/)
  [![Stars](https://img.shields.io/github/stars/MarceloHarbs/P10Documentacao?style=social)](https://github.com/MarceloHarbs/P10Documentacao/stargazers)
  [![Fork](https://img.shields.io/github/forks/MarceloHarbs/P10Documentacao?style=social)](https://github.com/MarceloHarbs/P10Documentacao/network/members)
  [![Watchers](https://img.shields.io/github/watchers/MarceloHarbs/P10Documentacao?style=social)](https://github.com/MarceloHarbs/P10Documentacao/watchers)
  
</div>

<a name="readme-top"></a>
<div align="center">
  <a href="https://github.com/horodeski/HumildeTentativaDeFazerUmPortfolio">
    <!-- logo se tiver 
    <img src="src/assets/img/logo.png" alt="Logo" width="200" height="200">
-->
  </a>

  <h2 align="center">LOJAS P10!</h2>

  <p align="center">
    <i>Viva ao Máximo por 10: Desfrute de Grandes Compras com Pouco Dinheiro!</i>
    <br />
    <a href="https://github.com/MarceloHarbs/P10-Documentcao"><strong>Documentação »</strong></a>
    <a href="https://github.com/horodeski/P10FrontEnd"><strong>FrontEnd »</strong></a>
    <a href="https://github.com/horodeski/P10Mobile"><strong>Mobile »</strong></a>
    <a href="github.com/marcoandre/pi-backend"><strong>BackEnd »</strong></a>
  </p>
</div>

<details>
  <summary>Sumário</summary>
  <ol>
    <li>
      <a>Sobre o projeto</a>
      <ul>
        <li><a href="#situação-problema">Situação problema</a></li>
        <li><a href="#proposta">Proposta</a></li>
        <li><a href="#regras-de-negócio">Regras de negócio</a></li>
        <li><a href="#requisitos-funcionais">Requisitos funcionais</a></li>
        <li><a href="#requisitos-não-funcionais">Requisitos não funcionais</a></li>
      </ul>
    </li>
    <li>
     <a href="#contato">Contato</a>
     <ul>
        <li><a href="#equipe">Equipe</a></li>
        <li><a href="#professores">Professores</a></li>
     </ul>
   </li>
  </ol>
</details>

<hr />

### Situação Problema

O Sr. Eduardo, dono da loja de departamento P10 (desde 2010) notou que, com o aumento nas vendas e da popularidade da loja, os funcionários estavam tendo dificuldade para manter as informações sobre o estoque atualizadas.

Com esse aumento exponencial de compradores, o Sr. Eduardo reconheceu a necessidade de ter um sistema de controle de caixa e estoque. Os funcionários relataram dificuldades em acompanhar a entrada e saída de mercadorias do estoque, assim deixando as informações relacionadas aos produtos e vendas desatualizadas. Isso gerou gastos desnecessários e a perda de vendas, por causa da indisponibilidade de produtos, excesso de produtos com baixa demanda e ausência de produtos com alta demanda. 

Em segundo plano, o Sr. Eduardo quer aumentar a visibilidade e acesso à loja, criando uma loja online. Na loja online,  os usuários poderão cadastrar-se, efetuar compras e consultas de preço. O software auxiliaria a manter o estoque atualizado, evitando que hajam futuros problemas relacionados com a quantidade de produtos no estoque. Isso seria realizado através de um relatório mostrando a demanda, quantidade de produtos em tempo real para todos os funcionários que possuem acesso ao sistema.

### Proposta

O software tem como alvo principal corrigir e auxiliar a falta de gerenciamento do estoque e foco secundário na gestão de vendas da loja.

O sistema terá 4 níveis de usuário: Cliente, Estoque, Gerente.

- **Cliente** - Terá acesso à parte da loja do sistema, onde poderá efetuar cadastro e login, compras de mercadoria. 

- **Estoque** - Terá acesso à parte de monitoramento de mercadoria, onde ele poderá registrar, ler, atualizar e deletar mercadorias.

- **Gerente** - Terá acesso à relatórios, onde terão informações sobre vendas, lucros e receitas diárias, produtos mais vendidos, categorias de produtos, clientes frequentes, metas de vendas, promoções e descontos.
 
 <!--
- **Gerente** terá acesso à relatórios de vendas, com inoformações de quais que estão tendo maior , quais precisam ser , relatório de faturamento e vendase valor individual de cada produto. Terá acesso aos dois níveis anteriores para monitoramento.
-->

### Regras de negócio

- **RN001 - Controle de caixa:** O sistema deve permitir o registro de todas as transações de venda, incluindo a forma de pagamento e a emissão de notas fiscais.

- **RN002 - Gerenciamento de estoque:** O sistema deve permitir o controle do estoque da loja, possibilitando o registro de entrada e saída de produtos, atualização de preços, descrições e informações adicionais relacionadas aos produtos.

- **RN003 - Relatórios:** O sistema deve permitir a geração de relatórios para os funcionários, apresentando informações detalhadas sobre o estoque, vendas, compras e outras informações relevantes para o gerenciamento da loja.

- **RN004 - Atualização em tempo real:** O sistema deve atualizar em tempo real as informações do estoque, permitindo aos funcionários visualizar a disponibilidade de produtos a qualquer momento.

- **RN005 - Acesso restrito:** O sistema deve permitir a configuração de perfis de acesso restrito para os funcionários, garantindo que apenas pessoas autorizadas possam realizar alterações no estoque e no caixa.

- **RN006 - Facilidade de uso:** O sistema deve ser intuitivo e de fácil utilização pelos funcionários da loja, minimizando a necessidade de treinamento adicional.

- **RN007 - Suporte técnico:** O sistema deve contar com suporte técnico para solucionar eventuais problemas que possam ocorrer no uso do software.

- **RN008 - Gerar backup:** O sistema deve fazer backup regularmente para garantir a segurança dos dados do sistema.

- **RN009 - Fornecer informações claras sobre o produto:** O sistema deve fornecer as infromações relacionadas ao pedido do cliente (preço, quantidade, entrega/retirada) de forma clara ao consumidor.

- **RN010 - Política de trocas:** O sistema deve deixar claro a política de troca da loja, "A troca somente será aceita com recibo fiscal no prazo de 20 dias".

- **RN011 - Ofertas:** O sistema deve ter uma área destinada as promoções e ofertas da loja.

- **RN012 - Visto Recentemente:** O sistema deve mostar as últimas consultas de produto do cliente.

- **RN013 - Categorias:** O sistema deve categoprizar as mercadorias.

### Requisitos funcionais

**Entradas:**
- **R.F. 01 - Cadastro de usuários:** O sistema terá uma interface onde ocorrerá o cadastro de novos clientes.
  - **Dados necessários:** Nome completo, CPF, número de telefone, RG, e-mail, senha e login.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 02 - Autenticação de usuário:** Tem como funcionalidade autenticar o acesso ao sistema, verificando se o usuário pode acessa-lo, caso possa, o direcionando para o a págian principal de seu perfil de acesso
  - **Dados necessários:** Login, senha, nível de permissão. 
  - **Usuários:** todos os níveis de usuário.

- **R.F. 03 - Entrada de produto:** O sistema terá uma interface onde poderá colocar as informações referentes à chagada de produtos.
  - **Dados necessários:** Nome, quantidade.
  - **Usuários:** Usuário tipo Estoque.

- **R.F. 04 - Saída de produto:** O sistema terá uma interface onde poderá colocar as informações referentes à saída de produtos.
  - **Dados necessários:** Nome, quantidade.
  - **Usuários:** Usuário tipo Estoque.
  
- **R.F. 05 - CRUD de mercadoria:** O sistema terá uma interface onde poderá ser realizado o CRUD realacionado as infromações da mercadoria.
  - **Dados necessários:** Nome, produtor, código, quantidade, descrição, categoria e valor.
  - **Usuários:** Usuário tipo Gerente.

- **R.F. 06 - Categorias de mercadoria:** O sistema terá uma interface onde poderá ser realizado o CRUD de mercadorias.
  - **Dados necessários:** Nome e descrição.
  - **Usuários:** Usuário tipo Gerente.

- **R.F. 07 - Adicionar mercadoria ao carrinho:** O sistema terá a função do cliente adicionar mercadorias ao seus carrinho pessoal de compras.
  - **Dados necessários:** Infromações do produto e do cliente.
  - **Usuários:** Usuário tipo Cliente.

**Saídas:**
- **R.F. 08 - Reltaório de vendas:** Tem como finalidade devolver relatórios de vendas individuais de produto.
  - **Dados necessários:** Relatório em fromato de tabela.
  - **Usuários:** Usuário tipo Gerente.
  
- **R.F. 09 - Relatório quantidade de produto:** Tem como finalidade devolver uma relatário onde informará quais produtos estão acabando no estoque.
  - **Dados necessários:** Relatório em fromato de tabela.
  - **Usuários:** O sistema terá uma interface onde poderá colocar as informações referentes a chagada de produtos.

- **R.F. 10 - Pesquisa de mercadoria:** O sistema deve permitir que o usuário filter/pesquise entre as mercadorias.
  - **Dados necessários:** Nome da mercadoria ou categoria.
  - **Usuários:** todos os níveis de usuário.

### Requisitos não funcionais

- **R.N.F. 01 - Atuação:** O sistema deve ser capaz de lidar com o número necessário de usuários sem queda brusca de desempenho.

- **R.N.F. 02 - Portabilidade:** O sistema deve ser responsivo, sendo possível sua atulização em diversos dispositivos com alteração mínima

- **R.N.F. 03 - Manutenção:** O sistema deve ser de fácil manter e atualizar.

- **R.N.F. 04 - Segurança:** O sistema deve ser protegido contra acesso não autorizado.

- **R.N.F. 05 - Níveis de segurança:** O software terá diferentes tipos de acesso para cada tipo de login, tendo as permissões ideais a função de cada um.

- **R.N.F. 06 - Tecnologia Front-end:** Para a exibição o sistema desktop será desenvolvido no framework VUEJS.

- **R.N.F. 07 - Tecnologia Front-end:** Para a exibição o sistema mobile será desenvolvido no framework React-Native.

- **R.N.F. 08- Tecnologia Back-end:** O software será desenvolvido no framework Django.

- **R.N.F. 09 - Interoperabilidade:** O banco de dados será o Mysql.

- **R.N.F. 10 - Comfiabilidade:** O sistema deve ser confiável e atentar as necessidades do usuário.

- **R.N.F. 11 - Legais:** O sistema deve atender às exigências da LGPD (Leis Gerais da Proteção de Dados).

## Contato
#### Equipe

* [Geovana Sophia Horodeski](https://github.com/horodeski) - geovana.horodeski06@gmail.com 
 
* [Gregory Ribeiro](https://github.com/eugreg) - daiaegregory@gmail.com
  
* [Marcelo Harbs](https://github.com/MarceloHarbs) - mharbs614@gmail.com 

</ul>

#### Professores


* [Alann Perini](https://github.com/AlannKPerini) - alann.perini@ifc.edu.br
  
* [Marco André Mendes Lopes](https://github.com/marrcandre) - marco.mendes@ifc.edu.br


<div align="center">
  
  [![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
  [![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
  
  
</div>


