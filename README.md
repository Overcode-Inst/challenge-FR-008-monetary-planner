# 📋 Indíce

- [Proposta](#id01)
  - [O desafio](#id01.1)
  - [Requisitos](#id01.2)
    - [Requisitos funcionais ](#id01.2.1)
    - [Requisitos não funcionais ](#id01.2.2)
    - [Requisitos não obrigatórios](#id01.2.3)
- [Screenshots](#id02)
- [O que aprendi](#id03)
- [Mão a obra...](#id04)
- [Pré-requisitos](#id05)
- [Procedimentos de instalação](#id06)
- [Desafios similares e dicas ](#id07)
- [Autor](#id08)

# 🚀 Proposta <a name="id01"></a>

Assim como Linus Torvalds disse "Falar é fácil, me mostre o código". Nós desenvolvedores nunca vamos aprender a programar e desenvolver software sem efetivamente codar, é como tentar aprender a andar de bicicleta lendo livros e vendo vídeos.

E foi assim que essa abordagem nasceu, um roadmap baseado em projetos. A ideia em seu princípio é simples, essa é uma demanda, tente encarar como um desafio técnico e completá-lo em até 7 dias.

Ao completar, não esqueça de publicar no linkedin e adicionar #handsOnRoadmap

## :trophy: O desafio <a name="id01.1"></a>

<br />

Imagine que foi pedido a você para fazer uma página de cadastro, esse cadastro é para solicitar contato com uma empresa prestadora de serviços que montam festas e eventos.

Essa empresa presta serviços tanto para pessoas físicas quanto para pessoas jurídicas. E faz os mais variados eventos possíveis.
<br />

## :dart: Os requisitos<a name="id01.2"></a>

### :dart: Requisitos funcionais <a name="id01.2.1"></a>

<br />

Sua aplicação deve ter:

<br />

- Uma página de formulário que conste com os campos:

  - nome completo/Razão social
  - tipo de evento ou festa. (aniversário, reunião de empresa/workshop, coffee and meet, outro)
  - Quantidade estimada de pessoas (campo de mínimo e máximo)
  - e-mail de contato
  - cpf/cnpj
  - Tema da festa
  - idade da pessoa a queme a festa se destina, caso for um aniversário
  - sexo, caso seja um aniversário
  - Um campo como conheceu a empresa (dê um nome de sua escolha para a empresa).
  - O campo descrito acima deve permitir a escolha de uma das opções entre recomendação, facebook, instagram, anúncio do google/youtube, outro.

- Ao escolher outro em qualquer pergunta, deve ser possível específicar.
- Ao concluir e confirmar com o botão o formulário some, e aparece no lugar uma mensagem que o pedido foi recebido.
- Na parte da mensagem deve ter um botão para responder fazer novo pedido, que retorna para o formulário com todos os campos zerados.
- Os campos nome completo/razão social, quantidade de pessoas, tipo de evento ou festa,e-mail de contato
  ,cpf/cnpj e campo de como conheceeu a empresa são obrigatórios.
- Os campos de idade e sexo se tornam obrigatórios caso o tipo dee festa seja aniversário.
- Os demais campos são opcionais.
- A página de agradecimento deve também mostrar as respostar anteriores, mas não como ampos de input, apenas mostrando as perguntas e respostas.

#obs: nenhum dado deve ser realmente armazenado. Se acaso for armazenar dados busque sobre como tratar os dados sensíveis tais como cpf. Essa proposta é fictícia e só deve ter objetivo de treino.

### :dart: Requisitos não funcionais <a name="id01.2.2"></a>

<br />

É obrigatório a utilização de:

- ReactJs
- fazer deploy
- Usar formulários controlados do ReactJS.
- Utilização de formik ou useForm
- O uso de yup.
- A aplicação deve ter uma rota só, sendo a página de agradecimento apenas um componente que tem sua visualização condicionada.

<br />

### :pushpin: Requisitos não obrigatórios <a name="id01.2.3"></a>

<br />

Você será bem avaliado se usar:

<br />

- usar HTML semântico, como tags main, section...
- usar responsividade
- organizar e dividir bem os arquivos
- Componentizar e separar bem o que achar que deve
- Usar typeScript

<br />

# :camera_flash: Screenshots <a name="id02"></a>

<br />

## :iphone: Mobile design

## :iphone: Tablets design

## :desktop_computer: Desktop design

# :heavy_check_mark: O que aprendi <a name="id03"></a>

# 🛠 Mão a obra... <a name="id04"></a>

Você pode forkar esse projeto e reutilizar o readme e estrutura, mas também se sinta livre para mudar ela ou mesmo criar a sua.

# ☑️ Pré-requisitos para rodar <a name="id05"></a>

<br />

- [x] Editor de código de sua preferência (recomendado VS code)
- [x] Git
- [x] ?

<br />

# 📝 Procedimentos de instalação <a name="id06"></a>

<br />

Clone este repositório usando o comando:

```bash
git clone https://github.com/<meu_user>/<my-repo>.git
```

```bash
#processos adicionais aqui
```

<br />

# 👨🏾‍💻 Desafios similares e dicas <a name="id07"></a>

Antes ou depois de realizar esse desafio, você pode pegar desafios parecidos do front-end mentor ou similares. Isso te ajuda a fixar e melhorar. Vou deixar alguns a seguir, pode te ajudar a se inspirar.

O segredo aqui é fazer modelos parecidos até ganhar algum conforto com fazer algo com essas técnicas e esse modelo de desafio, então quem sabe pegar outros mais difíceis.

[Base Apparel coming soon page](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0)

<br>

[Intro component with sign-up form](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1)

<br>

[Interactive card details form](https://www.frontendmentor.io/challenges/interactive-card-details-form-XpS8cKZDWw)

<br>

Você também pode usar o dribbble para se inspirar.

[Dribbble](https://dribbble.com)

# :sunglasses: Autor <a name="id08"></a>

<br />

- Linkedin - [Jean Carlos De Meira](https://www.linkedin.com/in/jeanmeira/)
- Instagram - [@jean.meira10](https://www.instagram.com/jean.meira10/)
- GitHub - [JCDMeira](https://github.com/JCDMeira)
