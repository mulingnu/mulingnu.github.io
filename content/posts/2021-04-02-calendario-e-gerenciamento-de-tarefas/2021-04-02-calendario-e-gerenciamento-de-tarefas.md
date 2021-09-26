---
draft: true
resources: []
title: Instalando o Kernel Linux-Libre no Debian e derivados
pubdate: now
cover:
    image: "imgs/100gnu+freedo.png"
    # can also paste direct link from external site
    # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
    alt: "<alt text>"
    caption: "<text>"
    relative: false # To use relative path for cover image, used in hugo Page-bundles
---

# Software livre de gerenciamento de tarefas e calendário com sincronização entre GNU/Linux e Android

Os calendários digitais tornaram-se uma ferramenta essencial na vida de professores e profissionais que precisam da união entre organização e praticidade. Muito mais práticos que os tradicionais calendários de papel, oferecem sincronia entre computadores e dispositivos mobile. Infelizmente essas ferramentas de organização cotidiana também foram dominadas pelos softwares privativos, não respeitando as [liberdades essenciais](https://www.gnu.org/philosophy/free-sw.pt-br.html) do usuário. O *Google Calendar* é, possivelmente, a ferramenta mais utilizada, visto que vem instalado por padrão nos aparelhos Android  com Google e também sincroniza com computadores. Todavia, existem ferramentas livres que, ao serem configuradas, oferecem o mesmo resultado sem que tenhamos nossa privacidade invadida e dados pessoais coletados por essas empresas.

Hoje falaremos sobre o serviço [Disroot](https://disroot.org/en) e veremos como sincronizar o calendário com seu celular Android. Apesar do Disroot oferecer diversos serviços em sua plataforma, nessa postagem trataremos especificamente do calendário e deixaremos as outras ferramentas para postagens futuras. Lembrando que este texto visa celulares com “Android puro” (sem serviços e aplicações do *Google*) e com o catálogo de softwares livres [F-Droid](https://www.f-droid.org/) instalado.

---

## Registrando uma conta no Disroot e acessando o calendário

1. Acesse o site do Disroot através do endereço https://disroot.org/;

2. Acesse o menu superior **Services** e clique em [**Cloud**](https://disroot.org/en/services/nextcloud);

[![](https://blogdomulin.com.br/wp-content/uploads/2021/05/1-1024x556.jpg)](https://blogdomulin.com.br/wp-content/uploads/2021/05/1.jpg)</figure>

3. Na próxima página, clique em [**Sign up for Disroot**](https://user.disroot.org/pwm/public/newuser);

[![](https://blogdomulin.com.br/wp-content/uploads/2021/05/2-1024x557.jpg)](https://blogdomulin.com.br/wp-content/uploads/2021/05/2.jpg)</figure>

4. Você terá acesso a um formulário de inscrição. Ao responder e enviar o formulário, a equipe do Disroot pede um prazo de 48 horas para que sua conta seja criada, todavia, geralmente autorizam antes;

[![](https://blogdomulin.com.br/wp-content/uploads/2021/05/3-1024x557.jpg)](https://blogdomulin.com.br/wp-content/uploads/2021/05/3.jpg)</figure>

5. Quando sua conta for autorizada, entre com suas credenciais (usuário e senha) no site normalmente. A primeira tela que aparecerá será a do seu painel principal. Clique no ícone do calendário para ter acesso à ferramenta;

<figure class="aligncenter size-large">![](https://blogdomulin.com.br/wp-content/uploads/2021/05/4.jpg)</figure>

