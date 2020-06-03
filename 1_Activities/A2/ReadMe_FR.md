# Activité #A2 : Identifier et définir les sujets métiers manipulés par l'application

## L'Activité Métier
Il s'agit de définir précisement de quoi "parle" cette application 

## Le Mantra : 
Le meileur conseil pour cette activité est sans doute le suivant : 
> Définir - autant que possible - les activités en terme de __finalité__ (et non de __moyen__)

## Le Livrable
Le __Conceptionary__ est non seulement le livrable de cette activité, ...   
... Mais c'est également LE livrable de cette approche méthodologique car il constitue un "pivot" de la démarche !   
 
## Les Notions Clefs
Les notions clefs pour cette activité sont résumées dans le tableau ci-après :

<table>
    <thead>
        <tr>
            <th>Entrée de Conceptionary</th>
            <th>Cardinalité (Min-Max)</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>ID de Sujet</td>
            <td>1-1</td>
            <td>Peut-être un nombre ou une chaîne alpha-numerique aléatoire ; ou bien un mot ou une expression en "EnglishCamelCase"</td>
        </tr>
          <tr>
            <td>============</td>
            <td>Et pour chaque Language</td>
            <td>============</td>
        </tr>
        <tr>
            <td>Label préféré</td>
            <td>1-1</td>
            <td></td>
        </tr>
        <tr>
            <td>Label alternatif</td>
            <td>0-N</td>
            <td></td>
        </tr>
        <tr>
            <td>Description</td>
            <td>1-1</td>
            <td>The description must refers to others concepts (via the Concept ID) in order to prepare the work for building the future ontology</td>
        </tr>
        <tr>
            <td>Commentaire</td>
            <td>0-N</td>
            <td></td>
        </tr>
        <tr>
            <td>Exemples</td>
            <td>3-7</td>
            <td>Quelques individus/instances représentatives du sujet/concept</td>
        </tr>
    </tbody>
</table>



