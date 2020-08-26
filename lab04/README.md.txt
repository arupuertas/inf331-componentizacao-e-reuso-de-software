# Modelo para Apresentação do Lab04 - Serviços

## Tarefa 1

## Tarefa 2

## Tarefa 3

## Tarefa 4

### Serviços 

 * Título do serviço: Poemist
 
 * Breve descrição
	Serviço não recebe informação nenhuma e retorna uma lista de poemas aleatórios
	contendo nome, URL, título	
	
 * URL completa da requisição
	https://any-api.com:8443/https://www.poemist.com/api/v1/randompoems
	
 * Cabeçalho HTTP da chamada:
GET /https://www.poemist.com/api/v1/randompoems HTTP/2
Host: any-api.com:8443
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:80.0) Gecko/20100101 Firefox/80.0
Accept: */*
Accept-Language: pt-BR,pt;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate, br
Origin: https://any-api.com
Connection: keep-alive
Referer: https://any-api.com/poemist_com/poemist_com/console/_randompoems/randompoems
TE: Trailers
	
 * Cabeçalho HTTP da resposta:

access-control-allow-origin: *
cache-control: no-cache, private, max-age=172800
content-type: application/json
date: Wed, 26 Aug 2020 01:49:32 GMT
expires: Fri, 28 Aug 2020 01:49:30 GMT
server: cloudflare
vary: Origin
x-final-url: https://www.poemist.com/api/v1/randompoems
x-ratelimit-limit: 20
x-ratelimit-remaining: 18


 * Conteúdo da resposta:

[
  {
    "title": "The Last Song Of Camoens",
    "content": "The morning shone on Tagus' rocky side,\nAnd airs of summer swelled the yellow tide,\nWhen, rising from his melancholy bed,\nAnd faint, and feebly by Antonio led,\nPoor Camoens, subdued by want and woe,\nAlong the winding margin wandered slow,\nHis harp, that once could each warm feeling move\nOf patriot glory or of tenderest love,\nHis sole and sable friend (while a faint tone\nRose from the wires) placed by a mossy stone. \nHow beautiful the sun ascending shines\nFrom ridge to ridge, along the purple vines!\nHow pure the azure of the opening skies!\nHow resonant the nearer rock replies\nTo call of early mariners! and, hark!\nThe distant whistle from yon parting bark,\nThat down the channel as serene she strays,\nHer gray sail mingles with the morning haze,\nBound to explore, o'er ocean's stormy reign,\nNew lands that lurk amid the lonely main! \nA transient fervour touched the old man's breast;\nHe raised his eyes, so long by care depressed,\nAnd while they shone with momentary fire,\nArdent he struck the long-forgotten lyre.\nFrom Tagus' yellow-sanded shore,\nO'er the billows, as they roar,\nO'er the blue sea, waste and wide,\nOur bark threw back the burning tide,\nBy northern breezes cheer'ly borne,\nOn to the kingdoms of the morn. \nBlanco, whose cold shadow vast\nChills the western wave, is past!\nHuge Bojador, frowning high,\nThy dismal terrors we defy!\nBut who may violate the sleep\nAnd silence of the sultry deep;\nWhere, beneath the intenser sun,\nHot showers descend, red lightnings run;\nWhilst all the pale expanse beneath\nLies burning wide, without a breath; \nAnd at mid-day from the mast,\nNo shadow on the deck is cast!\nNight by night, still seen the same,\nStrange lights along the cordage flame,\nPerhaps, the spirits of the good,\nThat wander this forsaken flood\nSing to the seas, as slow we float,\nA solemn and a holy note!\nSpectre of the southern main,\nThou barr'st our onward way in vain, \nWrapping the terrors of thy form,\nIn the thunder's rolling storm!\nFearless o'er the indignant tide,\nOn to the east our galleys ride.\nTriumph! for the toil is o'er--\nWe kiss the far-sought Indian shore!\nGlittering to the orient ray,\nThe banners of the Cross display!\nDoes my heart exulting bound?\nAlas, forlorn, I gaze around: \nFeeble, poor, and old, I stand,\nA stranger in my native land!\nMy sable slave (ah, no! my only friend,\nWhose steps upon my rugged path attend)\nSees, but with tenderness that fears to speak,\nThe tear that trickles down my aged cheek!\nMy harp is silent,--famine shrinks mine eye,--\n'Give me a little food for charity!'",
    "url": "https://www.poemist.com/william-lisle-bowles/the-last-song-of-camoens",
    "poet": {
      "name": "William Lisle Bowles",
      "url": "https://www.poemist.com/william-lisle-bowles"
    }
  },
  {
    "title": "Er han borte al min Eje",
    "content": "Er han borte al min Eje?\n   Skal jeg ham ej meere see,\n   Skal jeg ham ej meere see\n                meere see?\nVaagner jeg paa Ladheds Leje,\nTil at gaae fortvilte Veje,\n   I den haarde Fødsels Vee?\nEr han borte &amp;c. &amp;c.\n      Sulamith skriger,\n      Løber og græder, og siger,\n      At hun har forloret\n      Den hende har kaaret.\n      Her er jeg, du arme!\n      Jeg vil mig vist forbarme.\nEja! al Jammer og Trængsel god Nat.\nEja! al Jammer og Trængsel god Nat.\n      Sejren er vunden.\n      Bruden har funden\n      Bruden har funden\nHendes den allerlivsaligste Skat har funden\n      Bruden har funden\nHendes den allerlivsaligste Skat.\n      Und mig den Glæde,\n      JEsu! at træde\n      Til, dine Fødder at kysse og væde\n                kysse og væde.\nEja! al Jammer &amp;c. &amp;c.\n   Ja! jeg vil dig ikke hindre.\n      Kys, toe, saa meget som du vil.\n   Dog maae du dig erindre,\n      Saa længe du er til,\n   Den Nat, jeg fuld af Dugens Taare\n   Vel banked'; men blev uden fore.\nJa JEsu! min Kierligheds Taare jeg blander\n   Med beskeste Lage, af Smerte i Barm\n                af Smerte i Barm.\nMin Ladhed jeg ævig og ævig forbander,\n   Som giorte mig denne fortvivlede Harm.\nJa JEsu! min &amp;c. &amp;c.\n      Til Lykke! ja til Lykke du,\n      Som fant ham. Hav ham ævig nu.\n      Tak den, som var din Siæl saa troe,\n      Og siung i Aanden himmel-froe:\n                 Hallelujah!\n      Men vaag, saa kier du har din Skat,\n      At vente ham ved Dag og Nat.\n                 Hallelujah.\n         Til Lykke! ja &amp;c. &amp;c.",
    "url": "https://www.poemist.com/hans-adolph-brorson/er-han-borte-al-min-eje",
    "poet": {
      "name": "Hans Adolph Brorson",
      "url": "https://www.poemist.com/hans-adolph-brorson"
    }
  },
  {
    "title": "Into The Evening",
    "content": "Out of crooked clouds priceless things grow.\nVery tiny things suddenly become important.\nThe sky is green and opaque\nDown there where the blind hills glide.\nTattered trees stagger into the distance.\nDrunken meadows spin in a circle,\nAnd all the surfaces become gray and wise...\nOnly villages crouch glowingly: red stars--",
    "url": "https://www.poemist.com/alfred-lichtenstein/into-the-evening",
    "poet": {
      "name": "Alfred Lichtenstein",
      "url": "https://www.poemist.com/alfred-lichtenstein"
    }
  },
  {
    "title": "Damascus, What Are You Doing To Me?",
    "content": "Lovers Card\n\nMy voice rings out, this time, from Damascus\nIt rings out from the house of my mother and father\nIn Sham. The geography of my body changes.\nThe cells of my blood become green.\nMy alphabet is green.\nIn Sham. A new mouth emerges for my mouth\nA new voice emerges for my voice\nAnd my fingers\nBecome a tribe\n\n return to Damascus\nRiding on the backs of clouds\nRiding the two most beautiful horses in the world\nThe horse of passion.\nThe horse of poetry.\nI return after sixty years\nTo search for my umbilical cord,\nFor the Damascene barber who circumcised me,\nFor the midwife who tossed me in the basin under the bed\nAnd received a gold lira from my father,\nShe left our house\nOn that day in March of 1923\nHer hands stained with the blood of the poem…\n\nI return to the womb in which I was formed . . .\nTo the first book I read in it . . .\nTo the first woman who taught me\nThe geography of love . . .\nAnd the geography of women . . .\n\nI return\nAfter my limbs have been strewn across all the continents\nAnd my cough has been scattered in all the hotels\nAfter my mother's sheets scented with laurel soap\nI have found no other bed to sleep on . . .\nAnd after the \"bride\" of oil and thyme\nThat she would roll up for me\nNo longer does any other 'bride' in the world please me\nAnd after the quince jam she would make with her own hands\nI am no longer enthusiastic about breakfast in the morning\nAnd after the blackberry drink that she would make\nNo other wine intoxicates me . . .\n\nI enter the courtyard of the Umayyad Mosque\nAnd greet everyone in it\nCorner to . . . corner\nTile to . . . tile\nDove to . . . dove\nI wander in the gardens of Kufi script\nAnd pluck beautiful flowers of God's words\nAnd hear with my eye the voice of the mosaics\nAnd the music of agate prayer beads\nA state of revelation and rapture overtakes me,\nSo I climb the steps of the first minaret that encounters me\nCalling:\n\"Come to the jasmine\"\n\"Come to the jasmine\"\n\nReturning to you\nStained by the rains of my longing\nReturning to fill my pockets\nWith nuts, green plums, and green almonds\nReturning to my oyster shell\nReturning to my birth bed\nFor the fountains of Versailles\nAre no compensation for the Fountain Café\nAnd Les Halles in Paris\nIs no compensation for the Friday market\nAnd Buckingham Palace in London\nIs no compensation for Azem Palace\nAnd the pigeons of San Marco in Venice\nAre no more blessed than the doves in the Umayyad Mosque\nAnd Napoleon's tomb in Les Invalides\nIs no more glorious than the tomb of Salah al-Din Al-Ayyubi…\n\nI wander in the narrow alleys of Damascus.\nBehind the windows, honeyed eyes awake\nAnd greet me . . .\nThe stars wear their gold bracelets\nAnd greet me\nAnd the pigeons alight from their towers\nAnd greet me\nAnd the clean Shami cats come out\nWho were born with us . . .\nGrew up with us . . .\nAnd married with us . . .\nTo greet me . . .\n\nI immerse myself in the Buzurriya Souq\nSet a sail in a cloud of spices\nClouds of cloves\nAnd cinnamon . . .\nAnd camomile . . .\nI perform ablutions in rose water once.\nAnd in the water of passion many times . . .\nAnd I forget—while in the Souq al-‘Attarine—\nAll the concoctions of Nina Ricci . . .\nAnd Coco Chanel . . .\nWhat are you doing to me Damascus?\nHow have you changed my culture? My aesthetic taste?\nFor I have been made to forget the ringing of cups of licorice\nThe piano concerto of Rachmaninoff . . .\nHow do the gardens of Sham transform me?\nFor I have become the first conductor in the world\nThat leads an orchestra from a willow tree!!\n\nI have come to you . . .\nFrom the history of the Damascene rose\nThat condenses the history of perfume . . .\nFrom the memory of al-Mutanabbi\nThat condenses the history of poetry . . .\nI have come to you . . .\nFrom the blossoms of bitter orange . . .\nAnd the dahlia . . .\nAnd the narcissus . . .\nAnd the 'nice boy' . . .\nThat first taught me drawing . . .\nI have come to you . . .\nFrom the laughter of Shami women\nThat first taught me music . . .\nAnd the beginning of adolesence\nFrom the spouts of our alley\nThat first taught me crying\nAnd from my mother's prayer rug\nThat first taught me\nThe path to God . . .\n\nI open the drawers of memory\nOne . . . then another\nI remember my father . . .\nComing out of his workshop on Mu'awiya Alley\nI remember the horse-drawn carts . . .\nAnd the sellers of prickly pears . . .\nAnd the cafés of al-Rubwa\nThat nearly—after five flasks of ‘araq—\nFall into the river\nI remember the colored towels\nAs they dance on the door of Hammam al-Khayyatin\nAs if they were celebrating their national holiday.\nI remember the Damascene houses\nWith their copper doorknobs\nAnd their ceilings decorated with glazed tiles\nAnd their interior courtyards\nThat remind you of descriptions of heaven . . .\n\nThe Damascene House\nIs beyond the architectural text\nThe design of our homes . . .\nIs based on an emotional foundation\nFor every house leans . . . on the hip of another\nAnd every balcony . . .\nExtends its hand to another facing it\nDamascene houses are loving houses . . .\nThey greet one another in the morning . . .\nAnd exchange visits . . .\nSecretly—at night . . .\n\nWhen I was a diplomat in Britain\nThirty years ago\nMy mother would send letters at the beginning of Spring\nInside each letter . . .\nA bundle of tarragon . . .\nAnd when the English suspected my letters\nThey took them to the laboratory\nAnd turned them over to Scotland Yard\nAnd explosives experts.\nAnd when they grew weary of me . . . and my tarragon\nThey would ask: Tell us, by god . . .\nWhat is the name of this magical herb that has made us dizzy?\nIs it a talisman?\nMedicine?\nA secret code?\nWhat is it called in English?\nI said to them: It's difficult for me to explain…\nFor tarragon is a language that only the gardens of Sham speak\nIt is our sacred herb . . .\nOur perfumed eloquence\nAnd if your great poet Shakespeare had known of tarragon\nHis plays would have been better . . .\nIn brief . . .\nMy mother is a wonderful woman . . . she loves me greatly . . .\nAnd whenever she missed me\nShe would send me a bunch of tarragon . . .\nBecause for her, tarragon is the emotional equivalent\nTo the words: my darling . . .\nAnd when the English didn't understand one word of my poetic argument . . .\nThey gave me back my tarragon and closed the investigation . . .",
    "url": "https://www.poemist.com/nizar-qabbani/damascus-what-are-you-doing-to-me",
    "poet": {
      "name": "Nizar Qabbani",
      "url": "https://www.poemist.com/nizar-qabbani"
    }
  },
  {
    "title": "Hamako mita sake ye zamane mein dam nahi",
    "content": "hamako mita sake ye zamane mein dam nahi\nhum se zamana khud hai zamane se hum nahi\nbefayada alam nahin, bekar gham nahi\ntaufiq de khuda to ye ne'amat bhi kam nahi\nmeri zuban pe shikava-e-ahl-e-sitam nahi\nmujhko jaga diya yahi ehsaan kam nahi\nya rab! hujum-e-dard ko de aur vus'aten\ndaman to kya abhi meri aankhen bhi naam nahi\nzahid kuch aur ho na ho maikhane mein magar\nkya kam ye hai ki shikava-e-dair-o-haram nahi\nshikwa to ek ched hai lekin haqiqatan\ntera sitam bhi teri inayat se kam nahi\nmarg-e-jigar pe kyon teri aankhen hain ashk-rez\nik saniha sahi magar itni aham nahi",
    "url": "https://www.poemist.com/jigar-moradabadi/hamako-mita-sake-ye-zamane-mein-dam-nahi",
    "poet": {
      "name": "Jigar Moradabadi",
      "url": "https://www.poemist.com/jigar-moradabadi"
    }
  }
]

 

	