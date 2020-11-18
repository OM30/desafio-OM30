# Introdução (Frontend):

Iremos fazer uma grande atualização e mudanças no nosso código. Por isso, é imprescindível que você saiba minimamente Ruby e Rails ao menos de forma prática. Algumas apps nossas são legadas, monolíticas, mesmo no front você irá precisar lidar com backend (mas fica tranquilo, te ajudaremos nisso).

O profissional que escreveu esse teste levou 4 horas para executar todos os passos descritos e obedecendo todos os critérios. Tempo é fundamental para nós, porém, vamos focar na qualidade do seu trabalho, por isso, leve o tempo que achar necessário.

## Avaliação:

Crie um CRUD de municipes (Exceto deletar). O municipe tem status ativo e inativo. Idealmente, só precisa ser 2 páginas: Listagem de CRUD (com opções para navegar), e o cadastro em si. 2 páginas é apenas uma sugestão, você é livre para montar o UI/UX da forma que achar melhor.

1. Ter uma entidade relacionada chamada `Munícipe`. Essa entidade cadastra cidadãos (pessoas) dentro de um município. As
   seguintes regras devem ser seguidas:

  1.1 -> Dados do munícipe: Nome completo, CPF, Email, Data nascimento, Telefone (código do pais e ddd), Foto e status.
  1.2 -> Todos os dados do munícipe são obrigatórios;
  1.3 -> CPF,Email devem ser válidos;
  1.4 -> Tenha atenção a data de nascimento. Valide os casos impossíveis/improváveis de serem válidos;
  1.5 -> Foto do munícipe deve ser tamanhos diferentes para servir vários casos.

2. Ter uma entidade relacionada chamada `Endereço`. Essa entidade salva o endereço relacionado ao municipe. As seguintes
   regras devem ser seguidas:

   2.1 -> Campos: CEP, Logradouro, complemento, bairro, cidade, UF e codigo IBGE;
   2.2 -> Todos os dados são obrigatórios, exceto complemento e código IBGE;
   2.3 -> Em termos de MVC, existe apenas a Entidade relacional endereço. O restante é dispensável;

## Regras de negócio:

1. Seu código backend não será avaliado, porém, contará pontos. Você precisa fazer funcionar o backend de forma correta as regras acima.
2. Filtrar municipes por dados dele e/ou de endereco. É livre a escolha do que deve ser feito.

## Dicas:

### UI/UX:
  1. É possível otimizar o tempo de cadastro do endereço a partir do UX. Do it and show us the code ;)
  2. Você deve minimizar o máximo possível a navegação do usuário. Como você faria isso?
  3. Gostamos de atualizar o UI/UX de nossas apps de tempos em tempos. Leve isso em consideração
  4. Nessa vaga, tudo relacionado a frontend será avaliado;

### Backend:
  1. Fazer funcionar no seu caso é suficiente, porém, utilizar boas práticas de backend bem como as convenções contará MUITO ALTO;

## Tools:

- Ruby, Ruby on Rails e Postgres são obrigatórios no backend;
- Elasticsearch/Kafta (opcional, plus);
- Você pode escolher as abordagens abaixo:

1. ActionView com AssetPipeline/Sprockets com vanilla JS ou jQuery com plugins;
2. ActionView com Webpacker com (vuejs preferencialmente, mas, é livre a escolha da lib/framework);
3. Criar uma SPA app separado (vuejs preferencialmente, mas, é livre a escolha da lib/framework);

Critérios:

1. TUDO, absolutamente TUDO, será olhado (sim, teremos carinho pelo seu tempo gasto e olharemos com destreza seu teste);
2. Esse teste é frontend, então, aqui é que avaliaremos você;
3. Backend é opcional para o seu caso, mas, utilizar boas práticas de backend bem como as convenções contará MUITO ALTO (muito mesmo);
4. Ver seu teste rodando em modo produção conta MUITO. Fica ao seu criterio se faz e em qual plataforma;
5. Lembre-se que o melhor de um profissional é sua atitude quanto a resolução de problemas. Interprete esse item como desejar ;)
