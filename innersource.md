---
marp: true
paginate: true
theme: uncover
class: invert
header: TDC Business 2022 - Trilha DESIGN DE CÓDIGO E XP - InnerSource
footer: Alan Braz, Research Software Engineer at IBM [alanbraz.com.br](http://alanbraz.com.br)
title: InnerSource
description: Aproveitando o modelo OpenSource para dentro do firewall

---

<style>
.green {
  color: #68f0f0;
}
.blue {
  color: #012d9c;
}
.small {
  font-size: 0.6em;
}
</style>

<!-- 
_paginate: false
_footer: "[original email thread](https://bit.ly/2Jfg7Zb)"
_class:  -->

> Typically, this has involved helping large companies make the transition to open source but we've also worked with companies on what we call
> **"inner sourcing"** -- that is, helping them to 
> **use open source development techniques within the corporation**, or with a cluster of key customers -- 
> even if they aren't ready to take the step all the way to releasing their software as a public open source project.

_Tim O'Reilly (2000)_

---

<!-- Scoped style -->
<style scoped>
section {
  font-size: 2.3em;
}
</style>

![bg right:33%](images/lock.jpeg)

## InnerSource

> é o uso das melhores  <span class="green">**práticas de desenvolvimento**</span> e o estabelecimento de uma  <span class="green">**cultura**</span> semelhante ao __OpenSource__ dentro das organizações para o desenvolvimento de software de código não aberto e/ou proprietário.

<span style="font-size: 0.6em;">__Alan Braz (2022)__</span>

<!--
InnerSource is a software development methodology that applies the lessons learned from decades of open source software development to the concerns of tech leads and developers working inside proprietary organizations. In this introductory level course, InnerSource experts Danese Cooper and Russell Rutledge draw on their own experiences at companies like PayPal, Nike, and more to describe how InnerSource methods solve real world issues. How do I get teams located in far flung locations, possibly speaking different languages, and using different tools to work together effectively? How do I teach teams to contribute code without disrupting each other's workflow? How can I encourage developers in one business unit to incorporate functionality in their products using features developed by a competing business unit? These are just a few of the concerns InnerSource can address. By the end of this course, you'll have a firm understanding of InnerSource's key practices (collaboration, transparency, and mentorship) and a solid grasp of how you can use them to transform your own team from average to excellent.
-->
---

##### Piggybacking InnerSource on to Agile and DevOps

[![w:550](images/agile.png)](https://www.youtube.com/watch?v=QWbxXp5-nOQ&list=PLsO2m5gtfktKNX8zflJB0T5KbTSclCqnr&index=2)

Mishari Muqbil (Zymple) - IS Summit 21 Part 2

---

<!-- _class: -->


### The Open Organization

#### Igniting Passion and Performance

Jim Whitehurst

<span class="small">ex-CIO Red Hat, ex-presidente IBM</span>

![bg right h:500](https://images-na.ssl-images-amazon.com/images/I/51BnqEWpSdL._SX335_BO1,204,203,200_.jpg)

---

<!-- backgroundImage: "linear-gradient(to top right, #012d9c, #031f67)" -->

![bg left:30%](https://dw1.s81c.com/developer-static-pages/open/en/home/images/open-enterprise.png)

<style scoped>
section {
  font-size: 2.3em;
}
li a {
  font-size: 0.8em;
}
</style>

## OpenSource

- Código-livre?
- Repositório público?
- Fork, code, commit, push, PR, merge
- <span class="green">Comunidade!</span> 
    - [opensource.guide](https://opensource.guide)
    - [opensource.org](http://opensource.org)
    - [www.ibm.com/opensource](http://www.ibm.com/opensource)

---

<!-- 
backgroundImage: 
_class: invert
_header: ""
_footer: ""
_paginate: false
-->

![bg h:700](images/community.png)

---

<!-- 
backgroundImage: 
_class:  -->

<style scoped>
td {
  font-size: 0.5em;
  padding: 20px;
}
</style>

| OpenSource | InnerSource|
| --- | --- | 
| Múltiplas empresas contribuem para o bem da comunidade | Times ou divisões contribuem para o bem da empresa |
| ![h:250](images/opensource.png) | ![h:250](images/innersource.png) |
| Author, Owner, <span class="blue">Maintainers/Committer, Contributors</span>, Community Members |  Product Owner, <span class="blue">Trusted Committer, Contributors/Guests</span>, Users |

---

<!-- _class: -->
<style scoped>
p a {
  font-size: 0.5em;
}
</style>

#### Papéis

![h:400](https://d2908q01vomqb2.cloudfront.net/7719a1c782a1ba91c031a682a0a2f8658209adbf/2021/09/28/InnerSource-Roles-1024x568.png)

[fonte: noise.getoto.net/tag/innersource](https://noise.getoto.net/tag/innersource/)

---

![bg right:35%](images/code.jpg)

### Vantagens

\+ Qualidade, Colaboração, Reuso

\- Gargálos, Silos, Frustração

= Inovação!

= Atração de novas gerações

---

![bg grayscale brightness:0.4 blur:5px](images/coworking.jpg)
<!-- backgroundImage: "linear-gradient(to top right, #012d9c, #031f67)" -->

<style scoped>
p a {
  font-size: 0.5em;
}
</style>

### Desafios

- Ferramentas - GitHub, GitLab...
- Automação - CI/CD, testes
- Transparência - descoberta, acesso
- Comunicação - documentação, feedback
- Vergonha - pressão spcial, qualidade
- Propriedade intelectual - especial
- Contrato com cliente

https://resources.github.com/innersource/fundamentals/
<!--

![bg left:30%](images/alan.jpg)

<!-- 
_backgroundImage: "linear-gradient(to top right, #0b4d02, #06423d)" 

<style scoped>
section {
  font-size: 2em;
}
</style>

## Alan Braz

- Profissional
    - 20 anos em desenvolvimento web
    - 17 anos de IBM: Consultoria e Pesquisa
- Estudante
    - Ba Ciência da Comp. 2005 Unicamp
    - Ms Eng. da Software 2013 Unicamp
- Pessoa
    - casado, 2 filhos (6,6), yorkshire, porquinho da india
    - musculação, taekwondo, corrida, basquete 
    
-->

---

# InnerSource@IBM

---

<!-- _backgroundColor: black -->
<!-- _backgroundImage: "" -->

![bg opacity:.4](https://www.ibm.com/cloud/architecture/images/hero_banner/lead-practices.png)

<style scoped>
section {
  font-size: 1.8em;
  text-align: left;
}
</style>

### Social Coding - IBM Garage Methodology

![w:650](images/garage.jpeg)

> As equipes podem contribuir para projetos 
> além de seu escopo e os desenvolvedores podem 
> colaborar para construir e melhorar o código do software. 
[practice_social_coding](https://www.ibm.com/garage/method/practices/culture/practice_social_coding/) [tool_github](https://www.ibm.com/garage/method/practices/code/tool_github/)

---

### Birth of InnerSource at IBM

[![w:550](images/olivia.png)](https://www.youtube.com/watch?v=1x9FV2f4QoE)

Olivia Buzek (IBM) - IS Summit 21 Part 1

--- 

![bg right:60%](images/ibm.png)

<style scoped>
section {
  font-size: 1.6em;
}
</style>

#### InnerSource a an Experience

- <span class="green">IaaE</span> é uma abordagem sistemática de <span class="green">reuso</span> através da adoção de ferramentas e práticas padronizadas com o objetivo de maximizar o impacto otimizando a  <span class="green">colaboração e co-desenvolvimento da Comunidade</span>.

---

![bg left:50%](images/target.png)

<style scoped>
section {
  font-size: 2em;
}
</style>

#### Princípios

- <span class="green">Consistência</span>
    - padronizar para escalar
- <span class="green">Repetibilidade</span>
    - processos e infraestrutura 
- <span class="green">Reuse</span>
    - remover tensão entre times
- <span class="green">Comunidade</span>
    - cultura colaborativa

---

<style scoped>
section {
  font-size: 1.6em;
}
</style>

#### Papéis da comunidade

- <span class="green">Exploradores</span>
    - novos contribuidores, usuários, participantes da Comunidade
- <span class="green">Contribuidores</span>
    - promovem melhorias, membros da Comunidade
- <span class="green">Trusted Committers</span>
    - Especialistas, promotores da Comunidade
- <span class="green">Starters</span>
    - iniciam o projeto, artefatos, ferramentas, código, criadores da Comunidade

![bg right h:550](images/iaae.png)

--- 

<!-- 
_class: 
_backgroundImage: 
-->

<style scoped>
section {
  text-align: left;
}
ul { 
  margin-left: 0px;
}
</style>

![bg left:40% h:500](images/tools.png)

### Ferramentas

- GitHub Enterprise, ZenHub
- GitHub pages
- Travis CI, Tekton
- OpenShift clusters
- Artifactory
- Slack, Mural
- Webex, Box, Sharepoint

---

<!-- 
_header: ""
_footer: "" 
-->

![bg](images/pool-public.jpeg)

![bg](images/pool-friends.jpeg)

![bg](images/pool-home.jpeg)

![bg](images/bath-tube.jpeg)


---

<!-- 
_class: 
_backgroundImage: 
-->

<style scoped>
section {
  font-size: 1.8em;
}
</style>

## Obrigado!

![h:80](https://innersourcecommons.org/images/logo.png)
[innersourcecommons.org](https://innersourcecommons.org/)

[Artigo InfoQ](https://www.infoq.com/articles/inner-source-open-source-development-practices/)

[Playlist no YT](https://www.youtube.com/playlist?list=PLsO2m5gtfktKNX8zflJB0T5KbTSclCqnr)

Podcast:
[pullrecast.dev](http://pullrecast.dev)

[![bg right:55% h:500](images/prc_yt.png)](http://canal.pullrecast.dev)
