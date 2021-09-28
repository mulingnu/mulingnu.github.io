---
title: "Software livre de gerenciamento de tarefas e calendário com sincronização entre GNU/Linux e Android"
date: 2021-04-02T21:29:01-03:00
draft: false
# authors: ["Dillon", "PCloud"]
description: "Como ter um calendário e aplicativo de organização pessoal com softwares livres"
featuredImage: "https://images.pexels.com/photos/1425099/pexels-photo-1425099.jpeg?crop=entropy&cs=srgb&dl=pexels-%D0%B0%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D0%B0%D1%80-%D1%86%D0%B2%D0%B5%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%B8%D1%9B-1425099.jpg&fit=crop&fm=jpg&h=853&w=1280"

tags: ["software livre", "calendário", "android", "GNU"]
categories: ["categoria"]
# series: ["getting-start"]

lightgallery: true

toc:
  auto: true
---
## Introdução

Os calendários digitais tornaram-se uma ferramenta essencial na vida de professores e profissionais que precisam da união entre organização e praticidade. Muito mais práticos que os tradicionais calendários de papel, oferecem sincronia entre computadores e dispositivos mobile. Infelizmente essas ferramentas de organização cotidiana também foram dominadas pelos softwares privativos, não respeitando as <a href="https://www.gnu.org/philosophy/free-sw.pt-br.html" target=_blank>liberdades essenciais</a> do usuário. O *Google Calendar* é, possivelmente, a ferramenta mais utilizada, visto que vem instalado por padrão nos aparelhos Android  com Google e também sincroniza com computadores. Todavia, existem ferramentas livres que, ao serem configuradas, oferecem o mesmo resultado sem que tenhamos nossa privacidade invadida e dados pessoais coletados por essas empresas.

Hoje falaremos sobre o serviço <a href="https://disroot.org/en" target=_blank>Disroot</a> e veremos como sincronizar o calendário com seu celular Android. Apesar do Disroot oferecer diversos serviços em sua plataforma, nessa postagem trataremos especificamente do calendário e deixaremos as outras ferramentas para postagens futuras. Lembrando que este texto visa celulares com “Android puro” (sem serviços e aplicações do *Google*) e com o catálogo de softwares livres <a href="https://www.f-droid.org/" target=_blank>F-Droid</a> instalado.


---

## Registrando uma conta no Disroot e acessando o calendário

1. Acesse o site do Disroot através do endereço **<a href="https://disroot.org/" target=_blank>https://disroot.org/</a>**;</br>

2. Acesse o menu superior **Services** e clique em **<a href="https://disroot.org/en/services/nextcloud" target=_blank>Cloud</a>**;

![](https://archive.org/download/3_20210927_20210927/1.webp)</br></br>

3. Na próxima página, clique em **<a href="https://user.disroot.org/pwm/public/newuser" target=_blank>Sign up for Disroot</a>**;

![](https://archive.org/download/3_20210927_20210927/2.webp)</br></br>

4. Você terá acesso a um formulário de inscrição. Ao responder e enviar o formulário, a equipe do Disroot pede um prazo de 48 horas para que sua conta seja criada, todavia, geralmente autorizam antes;

![](https://archive.org/download/3_20210927_20210927/3.webp)</br></br>

5. Quando sua conta for autorizada, entre com suas credenciais (usuário e senha) no site normalmente. A primeira tela que aparecerá será a do seu painel principal. Clique no ícone do calendário para ter acesso à ferramenta;

![](https://archive.org/download/3_20210927_20210927/4.webp)</br></br>

6. Com o calendário aberto, adicione uma tarefa qualquer a ele para efetuar os testes no celular. No meu caso coloquei uma chamada "*Escrever artigo para o blog*" no dia 3 de março;

![](https://archive.org/download/3_20210927_20210927/5.webp)

7. Dessa forma, finalizamos a construção de nossa conta com calendário no computador. O próximo passo será sincronizá-lo com o celular.

</br>

## Sincronizando o calendário no Android

1. Acesse o F-droid e procure pelo aplicativo **<a href="https://f-droid.org/en/packages/at.bitfire.davdroid/" target=_blank>DAVx⁵</a>** e clique em Instalar;

<img src = "https://archive.org/download/3_20210927_20210927/6.webp"></br></br>

2. Quando o F-Droid perguntar se deseja realmente instalar, clique em **Instalar**;

<img src = "https://archive.org/download/3_20210927_20210927/7.webp"></br></br>

3. Após instalado, abra o **DAVx⁵** e clique no “+” para adicionar uma conta;

<img src = "https://archive.org/download/3_20210927_20210927/8.webp"></br></br>

4. Na tela seguinte, clique em **Autenticar com usuário e URL**. No campo **URL base** escreva *cloud.disrootorg*, e nos campos **Usuário** e **Senha** coloque suas credenciais do Disroot;

<img src = "https://archive.org/download/3_20210927_20210927/9.webp"></br></br>

5. Aguarde a detecção de configuração. Logo depois, clique em **Criar Conta**;

<img src = "https://archive.org/download/3_20210927_20210927/10.webp"></br></br>

6. Na tela seguinte clique em **CALDAV** para ter acesso aos calendários de sua conta do Disroot;

<img src = "https://archive.org/download/3_20210927_20210927/11.webp"></br></br>

7. O programa solicitará autorizações em seguida. Conceda-as para conseguir sincronizar o serviço;

<img src = "https://archive.org/download/3_20210927_20210927/12.webp"></br></br>

8. Acesse o menu de configurações da sua conta;

<img src = "https://archive.org/download/3_20210927_20210927/13.webp"></br></br>

9. Clique em Intervalo de sincronização de calendários;

<img src = "https://archive.org/download/3_20210927_20210927/14.webp"></br></br>

10. Escolha o intervalo de tempo que você deseja que o **DAVx⁵** sincronize o calendário do celular com o calendário do **Disroot**. Eu coloco 15 minutos para que ele sempre permaneça sincronizado, mas você pode personalizar de acordo com suas necessidades;

<img src = "https://archive.org/download/3_20210927_20210927/15.webp"></br></br>

11. Agora você pode sincronizar o calendário desejado e fechar o **DAVx⁵**. Em seguida, abra o aplicativo de calendário padrão de seu Android;

<img src = "https://archive.org/download/3_20210927_20210927/16.webp"></br></br>

12. Note que a tarefa que eu havia acrescentado no computador pelo Disroot, também aparece no calendário do celular.

<img src = "https://archive.org/download/3_20210927_20210927/17.webp">
</br>
<img src = "https://archive.org/download/3_20210927_20210927/18.webp">

---

Espero que esse pequeno tutorial tenha te ajudado a se tornar um pouco mais LIVRE!

Abraços!

<p text align = right>Foto de <b><a href="https://www.pexels.com/pt-br/@lemonzandtea?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels" target=_blank>Александар Цветановић</a></b> no <b><a href="https://www.pexels.com/pt-br/foto/calendario-de-mesa-de-bloco-de-madeira-marrom-exibindo-13-de-setembro-1425099/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels" target=_blank>Pexels</p></b>
