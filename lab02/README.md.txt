# Lab02 - Data Flow & Mensagens

* Tarefa sobre catálogo de componentes
* Tarefa Web Components 1
* Tarefa web Components 2 

## Tarefa sobre catálogo de componentes

* Arquivo do notebook

## Tarefa Web Components 1

<dcc-trigger label="Mundo"
             action="news/world/politics"
             value="election usa">
</dcc-trigger>

<dcc-trigger label="Brasil P"
             action="news/brazil/politics"
             value="brazil election´s">
</dcc-trigger>

<dcc-trigger label="Brasil E"
             action="news/brazil/sport"
             value="mundial do palmeiras">
</dcc-trigger>

<dcc-trigger label="Bahia"
             action="news/brazil/sport"
             value="Bahia F.C contratou messi">
</dcc-trigger>

<dcc-lively-talk duration="0s"
                 character="doctor"
                 speech="I heard about a ">
  <subscribe-dcc topic="news/#/politics"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk duration="0s"
                 character="nurse"
                 speech="I heard about a ">
  <subscribe-dcc topic="news/brazil/#"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk duration="0s"
                 character="patient"
                 speech="I heard about a ">
  <subscribe-dcc topic="news/#"></subscribe-dcc>
</dcc-lively-talk>

## Tarefa Web Components 2 

<dcc-trigger label="Notícias" action="next/rss">
</dcc-trigger>

<dcc-rss source="https://www.wired.com/category/science/feed" publish="rss/science">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>

<dcc-rss source="https://www.wired.com/category/design/feed" publish="rss/design">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>


<dcc-aggregator publish="aggregate/science" quantity="2">
  <subscribe-dcc topic="rss/science"></subscribe-dcc>
</dcc-aggregator>

<dcc-lively-talk id="doctor"
                 duration="0s"
                 character="doctor"
                 speech="News ">
<subscribe-dcc topic="aggregate/science"></subscribe-dcc>
</dcc-lively-talk>


<dcc-lively-talk id="doctor"
                 duration="0s"
                 character="nurse"
                 speech="News ">
   <subscribe-dcc topic="rss/science"></subscribe-dcc>
</dcc-lively-talk>


<dcc-lively-talk id="doctor"
                 duration="0s"
                 character="patient"
                 speech="News ">
    <subscribe-dcc topic="rss/design"></subscribe-dcc>
</dcc-lively-talk>