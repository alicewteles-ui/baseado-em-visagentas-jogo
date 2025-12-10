<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<title>A Mulher que Caminha na Névoa</title>
<script src="https://cdn.jsdelivr.net/gh/klembot/twinejs@gh-pages/harlowe-3.3.5.min.js"></script>
</head>
<body>
<tw-storydata name="A Mulher que Caminha na Névoa" startnode="1" creator="Twine" creator-version="2.7.0" format="Harlowe" format-version="3.3.5" options="" hidden>

<tw-passagedata pid="1" name="Início" tags="" position="100,100" size="100,100">
A noite cai sobre a comunidade ribeirinha.  
A névoa rasteira cobre a trilha como se estivesse viva.  
Dizem que, quando ela aparece, **ela** aparece também.

Você sente que hoje algo vai acontecer…

[[Entrar na floresta->Floresta]]  
[[Voltar para casa->Casa]]
</tw-passagedata>

<tw-passagedata pid="2" name="Floresta" tags="" position="300,100" size="100,100">
A névoa sobe pelas suas pernas como dedos gelados.

Entre as árvores, você vê a silhueta de uma mulher.  
Ela não tem rosto — só um longo cabelo que toca o chão.

[[Se aproximar da mulher->Aproximacao]]  
[[Chamar por alguém->Chamado]]  
[[Tentar correr->Fuga]]
</tw-passagedata>

<tw-passagedata pid="3" name="Casa" tags="" position="100,300" size="100,100">
Você corre para casa e fecha a porta.  
Mas a névoa entra pelas frestas como se tivesse vida própria.

Do lado de fora, uma mulher pálida encosta o cabelo no vidro.

[[Abrir a janela->Janela]]  
[[Se esconder->Esconderijo]]  
[[Rezar->Rezar]]
</tw-passagedata>

<!-- Caminho da Floresta -->

<tw-passagedata pid="4" name="Aproximacao" tags="" position="500,100" size="100,100">
Você dá um passo. E outro.

A mulher levanta seu "rosto" invisível.

**“Eu não vim te assustar. Eu vim te lembrar.”**

Ela toca sua testa, e imagens de mulheres esquecidas tomam sua mente.

== Final: Guardião da Memória ==  
Você carrega agora as histórias que ela protege.

[[Recomeçar->Início]]
</tw-passagedata>

<tw-passagedata pid="5" name="Chamado" tags="" position="500,200" size="100,100">
Você chama por alguém.

A floresta responde apenas com silêncio.

A mulher surge a menos de um braço de distância…

== Final: Silêncio na Mata ==  
Ninguém ouviu seu chamado.

[[Recomeçar->Início]]
</tw-passagedata>

<tw-passagedata pid="6" name="Fuga" tags="" position="500,300" size="100,100">
Você corre. Mas quanto mais corre, mais a névoa se densifica.

Algo segura seu braço.

A névoa toma forma de mulher.

== Final: Devorado pela Névoa ==  
Agora você é mais uma sombra da floresta.

[[Recomeçar->Início]]
</tw-passagedata>

<!-- Caminho da Casa -->

<tw-passagedata pid="7" name="Janela" tags="" position="300,300" size="100,100">
Você abre a janela.

A mulher entra devagar.  
Ela toca seu peito. Um calor estranho se espalha.

**“Corra quando tiver medo.  
Volte quando quiser saber.”**

== Final: Aquele que Escutou ==

[[Recomeçar->Início]]
</tw-passagedata>

<tw-passagedata pid="8" name="Esconderijo" tags="" position="300,400" size="100,100">
Você se esconde debaixo da cama.

A névoa entra. Entra. Entra.  
E para.  
Bem ao seu lado.

== Final: Respirando na Névoa ==

[[Recomeçar->Início]]
</tw-passagedata>

<tw-passagedata pid="9" name="Rezar" tags="" position="300,500" size="100,100">
Você começa a rezar.

A névoa recua…  
Mas a mulher sussurra atrás de você:

**“A fé protege.  
Mas não esconde a verdade.”**

== Final: A Prece e o Sussurro ==

[[Recomeçar->Início]]
</tw-passagedata>

</tw-storydata>
</body>
</html>
