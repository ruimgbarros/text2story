---
# try also 'default' to start simple
theme: default
fonts:
  sans: Avenir Next
  mono: Fira Code
  provider: Google
highlighter: shiki
info: |
  ## Hack the narrative
  Author: Rui Barros
# persist drawings in exports and build
drawings:
  persist: false
---
<span class="text-7xl">💻</span>
# Hack the narrative
<h2>How data is changing the news</h2>

<div class="uppercase text-sm tracking-widest mt-8">
Rui Barros
</div>



---
layout: 'intro'
---

# Rui Barros

<div class="leading-8 opacity-80">
Data journalist at PÚBLICO.<br>
Journalist that became a developer involuntarily.<br>
The guy that does ✨ I N T E R A C T I V E ✨ stuff at publico.pt.<br>
</div>

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/ruimgbarros" target="_blank">ruimgbarros</a></div>
  <ri-user-3-line class="opacity-50"/>
  <div><a href="https://ruimgbarros.com/" target="_blank">ruimgbarros.com</a></div>
  <ri-mail-line class="opacity-50"/>
  <div>rui.barros@publico.pt</div>
</div>

<img src="https://ruimgbarros.com/img/rui_barros.jpg" class="rounded-full w-40 abs-tr mt-16 mr-12"/>
---
layout: section
---
# What is <br> data journalism?
---
layout: section
---
<center class="text-9xl">
    🎲
</center>
---
layout: quote
---
## "What makes data journalism different to the rest of journalism? Perhaps it is the new possibilities that open up when you combine the traditional ‘nose for news’ and ability to tell a compelling story, with the sheer scale and range of digital information now available."

<a href="https://datajournalism.com/read/handbook/one/introduction/what-is-data-journalism">"What Is Data Journalism?"</a>
---
layout: center
---
<a href="https://www.theguardian.com/news/datablog/2011/sep/26/data-journalism-guardian">
    <img src="/static/ManchesterGuardian1821.png" class="h-92">
    <p class="mt-2 text-xs text-center opacity-60">The Manchester Guardian, Maio 1821</p>
</a>
---
layout: center
---
<a href="https://www.theguardian.com/news/datablog/2011/sep/26/data-journalism-guardian">
    <img src="https://ia600509.us.archive.org/BookReader/BookReaderPreview.php?id=precisionjournal00meye&subPrefix=precisionjournal00meye&itemPath=/5/items/precisionjournal00meye&server=ia600509.us.archive.org&page=leaf1&fail=preview&&scale=8&rotate=0" class="h-92">
    <p class="mt-2 text-xs text-center opacity-60">Precision Journalism (Meyer, 1973) </p>
</a>
---
layout: center
---
<figure class="max-w-xl mx-auto">
    <img src="https://media.npr.org/assets/img/2012/10/30/univac1_custom-a8caca6b3bf6519d6d49676c135f0008e3441ff6.jpg" class="mx-auto w-screen" alt="">
    <figcaption class="mt-2 text-sm opacity-50">
      CBS used the Univac I to predict the 1956 presidential election. They didn't run the numbers. Computer was right.
    </figcaption>
  </figure>

---
layout: image-left
image: https://i.guim.co.uk/img/media/c2a32990f3ec1ad099162df463b42af333eae940/0_287_2460_2548/master/2460.jpg?width=1010&quality=85&auto=format&fit=max&s=76f09a4d3d3e12d2850cf80cb51c3198
---

# What was stopping them?

<ul class="list">
  <li>💸 Expensive computing power </li>
  <li>🤔 No one knew how to use the computer</li>
  <li>💾 There was not that many data around</li>
  <li>🤑 Collecting and storing data was expensive</li>
</ul>

<style>
.list {
  list-style: none;
  margin: 0;
}
.slidev-layout li {
  margin-left: 0em;
}
</style>

---
layout: cover
background: static/publico_newroom.jpg
---
# Can you guess what happened next?
---
layout: center
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/h2zbvmXskSE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
---
layout: image-left
image: https://images.unsplash.com/photo-1623039405147-547794f92e9e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1052&q=80
---

# The data journalism workflow

<ol class="list">
    <!-- Tranlate the following lists -->
    <li>There is a theme, an idea, an <b>hypothesis</b>, new info in the newsroom</li>
    <li>We gather the data</li>
    <li>We clean the data</li>
    <li><b>We interview the database</b></li>
    <li>We start asking questions based on our data</li>
    <li>Think about the best way to tell this story</li>
    <li>Publish</li>
</ol>
---
layout: image-left
image: https://images.unsplash.com/photo-1623039405147-547794f92e9e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1052&q=80
---

# The data journalism workflow

<ol class="list">
    <li>There is a theme, an idea, an hypothesis, new info. in the newsroom</li>
    <li class="underline">We gather the data</li>
    <li class="underline">We clean the data</li>
    <li class="underline">We interview the database</li>
    <li>We start asking questions based on our data</li>
    <li>Think about the best way to tell this story</li>
    <li>Publish</li>
</ol>
---
layout: cover
background: https://pbs.twimg.com/media/C46hhG_UoAAXeS6.jpg
---
<h1>Why programming?</h1>
---
layout: image-right
image: https://cdn-media-1.freecodecamp.org/images/1*07n6A78xm2DwOM0mbeGvVA.jpeg
---
# Why programming in journalism?

- Reproducibility
- Transparency
- Automation
- Collaboration
- Data wrangling
- Data visualization
---
layout: center
---
<div class="flex flex-col">
    <img src="https://ih1.redbubble.net/image.398734614.2498/st,small,507x507-pad,600x600,f8f8f8.u2.jpg" class="h-92">
    <a href="https://inspectelement.org/apis.html" target="_blank" class="text-center">Finding Undocumented APIs</a>
</div>
---
layout: center
---
<a href="https://www.publico.pt/interactivo/quanto-estou-pagar-por-combustiveis-onde-estao-postos-mais-baratos" target="_blank">
    <img src="/static/preco_combustiveis.png">
</a>
---
layout: center
---
<img src="/static/publicoR_template.png" class="h-92">
---
layout: center
---
<img src="/static/publicoR.png" class="h-92">
---
layout: cover
background: https://images.unsplash.com/photo-1605289982774-9a6fef564df8?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=928&q=80
---
# Covid-19 contracts
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Getting the data
- The portuguese government was publishing a weekly updated excel file with all public contracts made under Decreto-Lei n.º 10-A/2020...
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Getting the data

- The portuguese government was publishing a weekly updated excel file with all public contracts made under Decreto-Lei n.º 10-A/2020...
- ... but data was missing

---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Getting the data
- We knew all the other contracts were being published on Portal BASE
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Getting the data

- We knew all the other contracts were being published on Portal BASE.
- But how could we get the data from there?
---
layout: image-left
image: static/scraper.jpg
---
# The scraper

- Started with around 30 keywords
---
layout: image-left
image: static/scraper.jpg
---
# The scraper

- Started with around 30 keywords
- Analysing the contracts term-frequency, we ended up with 98 words connected with covid contracts.

---
layout: fact
---
# 15.437

#### public contracts (after cleaning false positives)
---
layout: section
---
<div class="flex justify-center">
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
</div>

# The classification problem

---
layout: section
---
<img src="/static/mara.png" class="mx-auto" style="height:40vh;"/>
---
layout: section
---
<img src="/static/manchete.png" class="mx-auto" style="height:40vh;"/>
---
layout: section
---
<a href="https://www.publico.pt/interactivo/gastos-covid-19#/" target="_blank" rel="noopener noreferrer">
<img src="/static/newsapp.png" class="mx-auto" style="height:40vh;"/>
</a>
---
layout: center
---
<a href="https://www.publico.pt/interactivo/risco-covid-19-vacinado-nao-vacinado-o-que-fazer-seguranca-meu-concelho" target="_blank" rel="noopener noreferrer">
    <img src="/static/risco_covid.png" class="h-56">
</a>
---
layout: center
---
<img src="/static/hackTheNewsroom.png" class="h-96">
---
layout: section
---
<img src="/static/question.png" class="mx-auto h-30 mb-10"/>
