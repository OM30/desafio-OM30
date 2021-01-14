# Introdução (Backend):

> Iremos fazer uma grande atualização e mudanças no nosso código. Por isso, é imprescindível que você saiba Ruby e Rails. Algumas apps nossas são legadas, monolíticas, mesmo no backend você irá precisar lidar com um pouco com frontend (mas fica tranquilo, te ajudaremos nisso).

> O profissional que escreveu esse teste levou 4 horas para executar todos os passos descritos e obedecendo todos os critérios.Tempo é fundamental para nós, porém, vamos focar na qualidade do seu trabalho, por isso, leve o tempo que achar necessário.

## Avaliação:

Crie um CRUD de municipes (Exceto deletar). O municipe tem status ativo e inativo. Idealmente, só precisa ser 2 páginas: Listagem de CRUD (com opções para navegar), e o cadastro em si. 2 páginas é apenas uma sugestão, você é livre para montar o UI/UX da forma que achar melhor.

1. Ter uma entidade relacionada chamada `Munícipe`. Essa entidade cadastra cidadãos (pessoas) dentro de um município. As seguintes regras devem ser seguidas:

  1.1 -> Dados do munícipe: Nome completo, CPF, Email, Data nascimento, Telefone (código do pais e ddd), Foto e status.
  1.2 -> Todos os dados do munícipe são obrigatórios;
  1.3 -> CPF,Email devem ser válidos;
  1.4 -> Tenha atenção a data de nascimento. Valide os casos impossíveis/improváveis de serem válidos;
  1.5 -> Foto do munícipe deve ser tamanhos diferentes para servir vários casos.

2. Ter uma entidade relacionada chamada `Endereço`. Essa entidade salva o endereço relacionado ao municipe. As seguintes regras devem ser seguidas:

   2.1 -> Campos: CEP, Logradouro, complemento, bairro, cidade, UF e codigo IBGE;
   2.2 -> Todos os dados são obrigatórios, exceto complemento e código IBGE;
   2.3 -> Em termos de MVC, existe apenas a Entidade relacional endereço. O restante é dispensável;

## Regras de negócio:

1. Após criar/atualizar um municipe, você deve mandar um Email e sms ao mesmo informando sobre o cadastro de suas informações e quando o seu status sofrer alteração;
2. Filtrar municipes por dados dele e/ou de endereco. É livre a escolha do que deve ser feito.

## Dicas:

### UI/UX:
  1. É possível otimizar o tempo de cadastro do endereço a partir do UX. Do it and show us the code ;)
  2. Você deve minimizar o máximo possível a navegação do usuário. Como você faria isso?

### Backend:
  1. Pense que essas regras podem ser mudadas com uma frequência alta;
  2. Gostamos de otimização, setups e deploys são sempre automatizados;
  3. Não preciso dizer que você precisa testar, não é mesmo?
  4. Princípios e padrões de projetos são muito bem vindos;

## Tools:

- Ruby, Ruby on Rails e Postgres são obrigatórios;
- Elasticsearch/Kafta (opcional, plus);
- Utilize ActionView, porém, AssetPipeline/Sprockets ou uma abordagem SPA junto ao rails;

Critérios:

1. TUDO, absolutamente TUDO, será olhado (sim, teremos carinho pelo seu tempo gasto e olharemos com destreza seu teste);
2. Esse teste é backend, então, pesará muito como você realizou;
3. Frontend é opcional para o seu caso, mas, irá contar muito positivo como você fará;
4. Ver seu teste rodando em modo produção conta MUITO. Fica ao seu criterio se faz e em qual plataforma;
5. Lembre-se que o melhor de um profissional é sua atitude quanto a resolução de problemas. Interprete esse item como desejar ;)


Email para dúvidas: desenvolvimento@om30.com.br
