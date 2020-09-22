<h1 align = "center">
    <img alt = "Prescon Informática" src = "http://www.presconinformatica.com.br/img/logo_prescon.png" />
    <br>
    Fichas Squad Prescon Informática - Equipe Ubatuba
</h1>

<h4 align = "center">
  Neste repositório consta todas fichas desenvolvidas pela equipe de Ubatuba separadas por dia.
</h4>
<p align = "center">
  <img alt = "Tecnologia" src = "https://img.shields.io/badge/apex--oracle-100%25-blue">
</p>


Afim de organizar e descentralizar as fichas desenvolvidas a cada dia pela equipe, foi criado este repositório, onde abaixo segue as instruções de como qualquer funcionário que integre a equipe possa utilizar.

# Clone este repositório
$ git clone https://github.com/hallancma/Fichas-Squad-Ubatuba

# Ciclo de trabalho
<p>:one: Abra a pasta referente ao dia de trabalho. </p>
<p>:two: Crie a pasta contendo o seguinte padrão: XXX1234 (X = 3 iniciais da fichas e o restante é o número dela).</p>
<p>:three: Após realizar todo processo de conclusão da ficha e atualizado no sistema web da Prescon, salvar todos
scripts, pages e documento padrão de entrega dentro desta pasta.</p>
<p>:four: Para realizar o commit deve-se seguir exatamento o padrão abaixo, conforme o exemplo:</p>

Ex: Terminei a ficha AED1234, o procedimento deve ser:

<p>:arrow_right: git pull (Para atualizar seu repositorio local com o github);</p>
<p>:arrow_right: git add . ;</p>

<p>:arrow_right: git commit -m "mensagem" ;</p>

# Padrão de mensagem do commit:
<p>
Nos casos onde o solicitante for diferente do executante a mensagem do commit seria da seguinte forma: <br>
    <b>AED007 | Solit: Stocco | Exec: Hallan | Conferir no: Demonstração</b>
</p>

<p>
 Nos casos o solicitante for igual ao executante a mensagem do commit seria da seguinte forma:<br>
    <b>AED007 | Solit: Hallan | Exec: Hallan | Conferida OK</b>   
</p>

<p>
No caso acima não foi preciso inserir o campo "Conferir no", pois o mesmo funcionário que subiu
a fichas nos servidores trabalhados, é o mesmo responsábel pela conferência.Com isso a ficha 
já vai para você testada.     
</p>




<h3>
O funcionário é responsável por subir nos servidores 80(Desenvolvimento) e (98)Homologação e caso o mesmo precisou fazer alguma alteração direto no cliente ou no Demonstração o mesmo também será o responsável por subir neste ambiente.
</h3>

<p>:arrow_right: git push ou git push origin master  (Para enviar suas modificações para o github) ; </p>

<br>
<p><b>Obs. 2:</b> Caso a ficha seja um retorno basta informar o nome da pasta como "XXX1234-Retorno"</p>

#### Obs. 3: Se por engano você escreveu alguma mensagem de commit errada, veja como resolver aqui [alterar mensagem de commit](https://github.com/nemuba/change-commit-message)




---

Dúvidas ou sugetões, basta abrir uma issues. Caso algum membro da equipe tenha dúvidas com os comandos git segue o link dos comandos básicos para auxílio: http://rogerdudler.github.io/git-guide/index.pt_BR.html" 
