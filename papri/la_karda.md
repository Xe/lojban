---
title: la karda
---

<link rel="stylesheet" type="text/css" href="/files/normalize.css">

# la karda

> by ldlework

## Preface

This is a distilled overview of the Lojban language.

Major concepts of the language are introduced by saying as much with as
little as possible.

That is to say:

  - For each concept the most crucial aspects are presented
  - However, some details may be glossed over or simplified
  - Some details are only mentioned or explained by their mere
    appearance in example sentences. Look carefully\!

*Finally, some aspects of Lojban are omitted entirely\!*

However incomplete - the goal of the following is to present, in the
most immediate and expedient manner possible, a **conceptualization** of
the language. Lojban is characterized in many ways from being "logical"
and "unambiguous" to "culturally neutral". The characterization that
this text aims to reveal is that Lojban is both rational (it makes
sense) and regular (it always works the same).

From this rationality and regularity comes a simplicity that makes
Lojban easier to learn than anyone really ever expects it to be at
first.

**Tip:**

`   If you take the following passages at reading speed you will likely find`  
`   yourself lost in the forest very quickly. The slower you go, the better luck`  
`   you'll have at absorbing what it is trying to tell you.`

`   In the end, if you're confused, use that as inspiration to dig deeper and you'll`  
`   be fine!`

### Special Thanks

A number of people have contributed to the creation of this document in
various ways:

A general thanks goes to the entire IRC community, since it is the
largest driver of Lojban's on-going promotion and evolution.

Thanks goes to `la selpa'i ku` who's article on ZAhO was the inspiration
for the section on "Understanding Time" and has made a number of
corrections to errors in this document as well as helping along my own
study of Lojban. And of course their many contributions to the language
itself.

Additional thanks to those who have contributed minor corrections:

`la ilmen, la cirko, la kalmari, la gleki, la tsani, la lalxu`

## Core Grammar

### Parts of Language

In Language there are three major parts:

` nouns: the things we talk about`

` verbs: tell us what the nouns do`

` sentences: says something using nouns and verbs`

### Types of Words

Lojban only has two kinds of words:

` particles: short words that perform grammar functions`

` verbs: tell us what nouns do`

### What about Nouns?

What about nouns?\!

` Hold that thought.`

### Standard Form

Every sentence follows the form:

` i x1 VERB x2 x3 xN`

`i` separates multiple sentences. The first noun appears before the
verb, additional nouns follow the verb.

### Verbs Say What Nouns Do

Verbs tell us what the nouns do:

` dunda: x1 donates gift x2 to beneficiary x3`

` [donor] dunda [gift] [benefactor]`  
`    ├──────┼──────┼────────┤`  
`   x1    verb     x2       x3`

### Simple Pro-nouns

Some particles act like pro-nouns:

` mi - me, the speaker`

` do - you, the listener`

` ti - this, something nearby`

### Verbs and Nouns

Nouns can be put in the places and the verb says what they do:

`   mi    dunda   ti        do`  
` [donor]   │   [gift] [beneficiary]`  
`    ├──────┼──────┼────────┤`  
`   x1    verb     x2       x3`

` "I give this to you."`

### Rearranging Nouns

Putting the nouns into different places changes what they do:

`   do*   dunda   ti        mi*`  
` [donor]   │   [gift] [beneficiary]`  
`    ├──────┼──────┼────────┤`  
`   x1    verb     x2       x3`

` "You give this to me."`

### Converting Verbs to Nouns

The particles `lo` and `ku` convert verbs to nouns from the x1 role:

` Pattern: lo VERB ku => NOUN from x1`

`    dunda: x1 donates gift x2 to beneficiary x3`  
`      ▼`  
`    verb`  
`    ┌─┴─┐`  
` lo dunda ku <== [donor] dunda [gift] [benefactor]`  
` ─────┬─────       ├──────┼──────┼────────┤`  
`     noun         x1    verb     x2       x3`

`lo dunda ku` creates a noun-description which refers to "a donor"

`   mi    dunda   ti    lo dunda ku`  
` [donor]   │   [gift] [beneficiary]`  
`    ├──────┼──────┼────────┤`  
`   x1    verb     x2       x3`

` "I gave this to a donor."`

### Complex Sentences

Using multiple verbs, complex sentences can be formed:

` mlatu: x1 is a cat`

` pinxe: x1 drinks beverage x2`

` ladru: x1 is milk`

` lo mlatu ku   pinxe   lo ladru ku`  
`  [drinker]      │     [beverage]`  
`      ├──────────┼─────────┤`  
`     x1        verb        x2`

`     "A cat drinks some milk."`

### The Drama of Language

The previous example can be thought of as a kind of stage-play, directed
by the Verb and starring the Nouns.

` Breakfast Time, a play by Pinxe!`

The Verb Director tells us what Roles are available and What Happens:

` Pinxe says, "x1 drinks beverage x2"`

` Story Outline: [drinker] pinxe [beverage]`

` SCRIPT:`  
`   1. A Drinker drinks!`  
`   2. A Beverage is imbibed!`

` CAST:`  
`   The lead Drinker       : lo mlatu ku (mlatu's x1 - "a cat")`  
`   The supporting Beverage: lo ladru ku (ladru's x1 - "some milk")`

` STAGE:`  
`   lo mlatu ku   pinxe   lo ladru ku    <= actors in the play`  
`    [drinker]      │     [beverage]     <= roles in the play`  
`        ├──────────┼─────────┤`  
`      role1    director    role2`

`       "A cat drinks some milk."`

### Rearranging Verbs

The particles of the SE family rearrange verbs:

` Pattern: SE VERB => VERB'`

The roles of the x1 and xN nouns, what they do, is swapped in the new
modified
verb:

` klama: x1 travels to destination x2 from origin x3 via route x4 in vehicle x5`

`            | X1          | VERB     | X2          | X3        | X4        | X5        |`  
`            | traveler    | klama    | destination | origin    | route     | vehicle   |`  
`   x1◄ ►x2  | destination | se klama | traveler    | origin    | route     | vehicle   |`  
`   x1◄ ►x3  | origin      | te klama | destination | traveler  | route     | vehicle   |`  
`   x1◄ ►x4  | route       | ve klama | destination | origin    | traveler  | vehicle   |`  
`   x1◄ ►x5  | vehicle     | xe klama | destination | origin    | route     | traveler  |`

` se klama: to destination x1, traveler x2 goes from origin x3 via route x4 in vehicle x5`  
` and so on..`

### SE In Action

These SE modified verbs are useful both in making nouns and as the main
verb of sentences:

` fraxu: x1 forgives x2 for x3`

` vecnu: x1 sells x2 to buyer x3 for price x4`

` dakfu: x1 is a knife`

` lo se fraxu ku  te vecnu   lo dakfu ku`  
`    [buyer]         |        [goods]`  
`       └────────────┴───────────┘`  
`      "The forgiven buys a knife."`

` friti: x1 offers x2 to x3`

` xamgu: x1 is beneficial to x2`

` ginka: x1 is an encampment of x2`

` lo se friti ku  xamgu   lo se ginka ku`  
`   [benefit]       |      [beneficiary]`  
`       └───────────┴───────────┘`  
`  "The offering is good for the campers."`

### FA Labels

The FA family of particles allows for breaking the default noun ordering
of sentences without modifying the verb:

` Pattern: FA NOUN => NOUN'`

` fa : x1   Each particle from the FA family`  
` fe : x2   simply specifies what the following`  
` fi : x3   noun is doing in the sentence. In`  
` fo : x4   other words which role from the verb`  
` fu : x5   it fills.`

This allows putting all of the nouns after the verb:

` dunda fa mi ti do - "I donate this to you"`

Or skip some places entirely:

` mi dunda fi do - "I donate to you"`

Counting resumes from any FA particle:

` fe ti dunda fa mi do - "I donate this to you"`  
` ──┬──       ──┬── ─┐`  
`  x2          x1   x3`

### Cmavo and Brivla

Lojban has names for the two kinds of words that make up its dictionary:

` "cmavo" - mi, ti, do, lo, ku`  
`    - small word that performs a grammatical function`  
`    - categorized into families`

` "brivla" : dunda, klama, mlatu, ladru`  
`    - a word that produces a grammatical verb`  
`    - has a definition with 1 or more noun roles`

### Selbri Sumti and Bridi

It also has names for the different parts of speech that come to life in
lojban sentences:

` "selbri" - the verb phrases central to sentences and nouns`

` "sumti" - the noun phrases that take on semantic roles`

` "bridi" - the combination of a selbri and its sumti`

`LEGEND:`  
`   <> - selbri verb`  
`   [] - sumti noun`  
`   {} - bridi statement`

Notice how selbri verb phrases appear throughout:

` lo <se `<jdice>`> ku `<nandu>` lo `<sonci>` ku`

Sumti nouns are placed around the root selbri:

` [lo se jdice ku] nandu [lo sonci ku]`

And the whole structure, a selbri with its sumti, is a bridi:

` {lo se jdice ku nandu lo sonci ku}`

### Tanru

By combining multiple consecutive independent selbri, a `tanru` or
compound-selbri verb can be created:

` mi <`<djica>` `<citka>`> lo `<plise>` ku`  
` "I want-eat an apple."`

Two brivla `cidja` and `dunda` come together below to create a
compound-selbri inside a sumti:

`       Simple Selbri`  
`        ┌───┴───┐`  
` lo <`<cidja>` `<dunda>`> ku `<prami>` lo `<prenu>` ku`  
`    └───────┬───────┘`  
`       Selbri Tanru`

` "The food-donor loves people."`

But what is the definition of a composite-selbri or tanru?

Tanru are metaphorical, so their full meaning is ambiguous. However,
basic structure of the definition is that of the **right most** selbri
component:

` gleki : x1 is happy about x2`

` cadzu : x1 walks on surface x2`

` gleki cadzu : x1 happy-walks on surface x2`

` What does "happy-walk" really mean? Only the speaker knows for sure!`

## Conversation

### Proper Nouns

Proper nouns are created by using `la` instead of `lo`:

` mi prami lo rozgu ku`  
`          ──       ──`  
` "I love roses."`

` mi prami la rozgu ku`  
`          ──       ──`  
` "I love Rose."`

` Names are sumti just like any other.`

### Introductions

Introducing one's own self is done with the cmavo `mi'e`:

` Pattern: mi'e NAME`

` mi'e la rozgu ku`  
` ────`  
` "I'm Rose."`

### Greetings

Greeting another person is done with the cmavo `coi`:

` Pattern: coi SUMTI`

` coi la rozgu ku`  
` ───`  
` "Hello, Rose."`

` coi lo tadni ku`  
` ───`  
` "Hello, student"`

` coi do`  
` ───`  
` "Hello, you."`

` Or just, "coi"`

### Farewells

Farewells are offered with the cmavo `co'o`:

` Pattern: co'o SUMTI`

` co'o la rozgu ku`  
` ────`  
` "Goodbye, Rose."`

### Requesting Attention

Requests for attention are made with the cmavo `ju'i`:

` Pattern: ju'i SUMTI`

` ju'i la rozgu ku`  
` ───`  
` "Hey, Rose."`

If multiple listeners paying attention you can address them individually
with `doi`:

` Pattern: doi SUMTI`  
` doi la mirli ku ko mipri`  
` ───`  
` "Keep it secret, Moose"`

### Yes No Questions

"Yes or No" questions can be asked by using the `xu` cmavo:

` i xu do citka lo plise ku`  
`   ──`  
` "Did you eat an apple?"`

Notice that even though the sentence is now a question rather than a
statement the overall structure hasn't changed.

The `xu` is placed after the sentence separator `i` so as to apply to
the whole sentence equally. By placing `xu` after a specific word
emphasis can be placed on it:

` i do citka lo xu plise ku`  
`               ──`  
` "Was it an apple you ate?""`

### Yes No Answers

"Yes" and "No" answers can be supplied with the following replies:

` In the affirmative, "go'i" is used:`  
`   Q: xu do citka lo plise ku`  
`   A: go'i`  
`      ───`  
` The denial is supplied by: na go'i`

### Sumti Questions

Sumti specific questions can be asked by using the `ma` cmavo in place
of the sumti in question.

` do citka ma`  
`          ──`  
` "What did you eat?"`

` ma catra ma`  
` ──       ──`  
` "Who killed who?"`

To answer sumti questions simply state what fills the missing place:

` lo plise ku`

Or restate the question with the places filled in:

` do catra mi`

### Selbri Questions

Selbri specific questions can be asked by using the `mo` cmavo in place
of the selbri in question.

` mo fa mi do ti`  
` ──`  
` "What are we doing with this?"`

` do mo`  
`    ──`  
` "You are/doing what?"`

` do mo fengu mi`  
`    ──`  
` "What kind of angry are you at me?"`

### Attitude Questions

A special kind of question using the cmavo `pei` asks the listener to
share their feelings or disposition about some topic:

` i pei mi cliva`  
`   ───`  
` "How do you feel about me leaving?"`

"pei" is another word which can direct its emphasis by way of
right-attachment:

` i mi jukpa lo jipci ku pei`  
`                        ───`  
` "How do you feel that its chicken that I cook.`

### Attitude Cmavo

In addition to making an explicit statement about one's self, an answer
to `pei` can be given with cmavo from the UI Family of "attitudinals".

` ui - "I'm happy"`

` a'o - "I hope"`

` i'e - "I approve"`

There are many attitudinals and they all express, in one way or another
some aspect of the speaker's disposition about the speech the
attitudinal is appears in.

` i ui do prami mi`  
`   ──`  
` "You love me, and I'm happy about it."`

` i a'o do snada`  
`   ───`  
` "I'm hopeful you succeed."`

Like many other cmavo, UI attitudinals give emphasis to the part of
speech they attach to:

` do pinxe lo birje ku e'u`  
`                      ───`  
` "I suggest beer to be what you drink."`

### Attitude Ranges

Attitudinals have an inherent "range" or "intensity spectrum" which can
be altered from the default.

Without any modifier you get the default attitude. However, `nai` and
other cmavo can affect the sense of the UI cmavo:

` ui cai     - "I'm happy as possible"`  
` ui sai     - "I'm very happy"`  
` ui         - "I'm happy"`  
` ui ru'e    - "I'm kinda/sorta happy"`  
` ui cu'i    - "I'm neutral in my happiness"`  
` ui nai     - "I'm unhappy"`  
` ui nai sai - "I'm very unhappy"`

and so on...

### Evidential Cmavo

A sub-family of the attitudinals, the UI2 Evidentials, express an
epistemological claim. In other words, how the speaker came to know or
state whatever it is they are saying:

` i ti'e do nelci mi`  
`   ────`  
` "I hear rumored that you like me."`

` i pe'i lo plise ku xamgu`  
`   ────`  
` "It is my opinion that apples are beneficial."`

` i za'a do mutce xagji`  
`   ────`  
` "I observe that you are very hungry."`

` i ba'a la rozgu ku zvati lo zdani ku`  
`   ────`  
` "I expect Rose is at the house."`

### Discursive Cmavo

Another sub-family of the attitudinals, the UI3 "discursives" express
the point or purpose of a part of or a whole statement.

` i do citka lo titla ku po'o`  
`                        ────`  
` "You only eat sweets."`

` i ji'a mi nitcu lo jdini ku`  
`   ────`  
` "Also, I need money."`

` i si'a mi terpa lo jukni ku`  
`   ────`  
` "Similarly, I'm afraid of spiders."`

` i ku'i lo jenmi ku daspo`  
`   ────`  
` "However, armys are destructive."`

### Humor

Having a sense of humor is key to any conversation:

Sarcasm:

` i xo'o lo se platu ku banli`  
`   ────`  
` "Oh jeeze, great plan."`

` i xo'o nai lo skaci ku melbi`  
`   ────────`  
` "Seriously, that skirt is beautiful."`

Levity:

` i zo'o se ckaji do`  
`   ────`  
` "Ho! Typical you."`

` i zo'o nai mi nelci lo cutci`  
`        ────`  
` "I do like these shoes..."`

Amusement:

` i u'i xu do mulno`  
`   ───`  
` "Haha, are you done yet?"`

` i u'i nai xu do mulno`  
`   ───────`  
` "Yea.. are you done yet?"`

### Changing the Subject

If things get tense you can always change the subject with `ta'o`:

` i ta'o do klama ma`  
`   ────`  
` "By the way, where are you going?"`

You can also return to a previous topic by adding `nai`:

` i ta'o nai mi'o casnu ma`  
`   ────────`  
` "Returning, what were we discussing?"`

### Requests and Commands

Ultimately if things go completely sour you may have to request your
interlocutor to leave:

` i e'o do cliva`  
`   ───`  
` "Please, you leave."`

Or if they have been particularly offensive you might demand it\!

` i ko cliva`  
`   ──`  
` "I implore you to leave."`

` Any command is possible by using "ko" in place of the normal "do".`

## Sumti Manipulation

### Saying "and" and "or"

To make statements about different sumti at the same time the connective
cmavo `je` can be used:

` Pattern: SUMTI je SUMTI => SUMTI'`

` i mi nelci [[lo plise ku] je [lo perli ku]]`  
`                           ──`  
` "I like apples and pears."`

Similarly, `ja` can be used for "or":

` i ko cuxna [[lo dakfu ku] ja [lo mruli ku]]`  
`                           ──`  
` "Pick the knife or the spear"`

### Grouping

To group multiple sumti together to say that they do something together,
`jo'u` can be used:

` Pattern: SUMTI jo'u SUMTI => SUMTI'`

` i [[mi] jo'u [do]] bevri lo pipno`  
`         ────`  
` "You and I carry the piano"`

` i mi se catra [[lo fagri ku] jo'u [lo bisli ku]]`  
`                              ────`  
` "I was killed by fire and ice."`

### Ownership

To associate one sumti with another by way of ownership the cmavo `po`
is used:

` Pattern: SUMTI po SUMTI => SUMTI'`

` i [[lo karce ku] po [mi]] spofu`  
`                  ──`  
` "My car is broken."`

` i ko cpacu [[lo ckiku ku] po [do]]`  
`                           ──`  
` "Go get your keys."`

### Association

For a weaker association than ownership you can use `pe`:

` Pattern: SUMTI pe SUMTI => SUMTI'`

` i mi vasxu [[lo vacri ku] pe [do]]`  
`                           ──`  
` "I'm breathing your air."`

` i ko zutse [[lo stizu ku] pe [mi]]`  
`                           ──`  
` "Sit in my chair."`

### Pluralities

To specify how many of a sumti there are, a number can be placed before
the sumti:

` Pattern: PA SUMTI => SUMTI'`

` Numbers:`  
`  no  pa  re  ci  vo  mu  xa  ze  bi  so`  
`   0   1   2   3   4   5   6   7   8   9`

` i mi viska [mu [lo bakni ku]]`  
`             ──`  
` "I see 5 cows."`

` i mi se raktu [so so [lo nabmi ku]]`  
`                ─────`  
` "I am troubled by 99 problems."`

### Subjective Numbers

Other kinds of "subjective numbers" exist too which are pretty handy:

` i xu do citka [du'e [lo plise ku]]`  
`                ────`  
` "Did you eat too many apples?"`

` so'u lo plise ku    - "a few apples"`  
` so'o lo plise ku    - "several apples"`  
` so'i lo plise ku    - "many apples"`  
` so'e lo plise ku    - "most of the apples"`  
`   ro lo plise ku    - "all the apples"`  
`  rau lo plise ku    - "enough apples"`  
` mo'a lo plise ku    - "not enough apples"`  
` da'a ci lo plise ku - "all but three apples"`

## Selbri Manipulation

### Negation and Affirmation

Most selbri manipulation is performed via prefix cmavo. For example
negation is done with `na`:

` Pattern: NA SELBRI => SELBRI'`

` i mi <na `<xagji>`>`  
`       ──`  
` "I'm not hungry"`

` On the flip-side you can say something is certain:`

` i mi <ja'a `<xagji>`>`  
`       ────`  
` "I am definitely hungry"`

### Scaling Relevance

Other cmavo have related effects which specify how strongly the selbri
is applied:

` i mi <no'e `<xagji>`>`  
`       ────`  
` "I'm not really that hungry."`

` i mi <to'e `<xagji>`>`  
`       ────`  
` "I'm full!"`

### Saying "and" and "or"

Similarly to sumti, selbri can be joined with the very same connective
words:

` i mi <`<tatpi>` je `<xagji>`>`  
`               ──`  
` "I'm tired and hungry"`

` i mi'o e'u <`<citka>` ja `<cliva>`>.`  
`                     ──`  
` "We should eat or leave."`

### Tense

While Lojban bridi don't have any implicit tense, selbri can be modified
to have such tense:

` mi <pu `<viska>`> do`  
`     ──`  
` "I saw you."`

` mi <ca `<viska>`> do`  
`     ──`  
` "I see you."`

` mi <ba `<viska>`> do`  
`     ──`  
` "I will see you."`

### Temporal Distance

In addition to direction, temporal distance can also be provided:

` mi <pu zi `<viska>`> do`  
`        ──`  
` "I just saw you!"`

` mi <pu za `<viska>`> do`  
`        ──`  
` "I saw you a while ago."`

` mi <pu zu `<viska>`> do`  
`        ──`  
` "It has been a long while since I've seen you."`

### Proximity

Selbri can also be modified in terms of spatial proximity:

` mi <vi `<viska>`> do`  
`     ──`  
` "I saw you right here!"`

` mi <va `<viska>`> do`  
`     ──`  
` "I saw you nearby."`

` mi <vu `<viska>`> do`  
`     ──`  
` "I saw you elsewhere."`

### Preloading

Selbri can be "pre-injected" with a sumti, removing a sumti place from
the definition, with the `be` cmavo:

` Pattern: SELBRI be SUMTI => SELBRI'`

` dunda : x1 donates gift x2 to beneficiary x3`  
` dunda be lo plise ku : x1 donates apples to beneficiary x2`

By default `be` injects a sumti into the x2 place, but the FA family can
be used to specify which place should be filled:

` vecnu be fi lo jecta ku : x1 sells x2 to the state`

Multiple sumti places may be filled, separated by `bei`:

` vecnu be lo xarci ku bei lo jecta ku : x1 sells weapons to the state`

### Preloaded Sumti

Note that `be` forms a new selbri even though it incorporates a sumti:

` ┌──────new selbri──────────┐`  
` <`<vecnu>`  be  [lo xarci ku]> = x1 sells weapons to x2`  
`     │               │`  
` base selbri   injected sumti`

This is a little strange when used as the main verb of a sentence:

`    (who)         (sells guns)       (the state)`  
`     ma     `<vecnu be lo xarci ku>`   lo jecta ku`  
`   [seller]             │              [buyer]`  
`      └─────────────────┴─────────────────┘`

`lo xarci ku` could just have been provided as x2 to a normal `vecnu`.
The `be` appears unnessecary. However, this is very useful for creating
interesting sumti\!

`              ┌───preloaded selbri─────┐`  
` mi tavla [lo <`<vecnu>` be [lo xarci ku]> ku]`  
` "I talk to the seller of weapons.`

` ko na lebna [lo <`<sidbo>` be fi [mi]> ku]`  
` "Don't you take ideas of mine."`

This is far more explicit than using `pe` or `po`.

## Subordination

### Facts

Similar to the transformation of selbri into sumti the same can be done
for whole bridi into selbri with the help of `du'u` and `kei`:

` Pattern: du'u BRIDI kei => SELBRI`

The definition of such a selbri is something like:

` x1 is the fact represented by the inner bridi`

` ┌───fact selbri────┐`  
` du'u do prami mi kei =  x1 is the fact that: you love me`  
`     └─────┬─────┘`  
`      inner bridi`

Adding `lo` and `ku`, the selbri is transformed into a sumti allowing
one to talk about the fact inside:

` [lo <du'u {do prami mi} kei> ku] = "the fact that you love me"`

These nested fact sumti can be used as any other:

`              ┌───fact selbri────┐`  
` mi djuno [lo du'u do prami mi kei ku]`  
`                  └─────┬─────┘`  
`                   inner bridi`

` "I know that you love me."`

### Events

Where `du'u` gets at the truth of a matter, `nu` can emphasize the time
and location in which a bridi takes place:

` Pattern: nu BRIDI kei => SELBRI`

The definition of such a selbri is something like:

` x1 is the event described by the inner Bridi`

` ┌──fact selbri───┐`  
` nu do speni mi kei =  x1 is the event of: you are married to me`  
`   └─────┬─────┘`  
`    inner bridi`

Just like with `du'u` these `nu` selbri can be turned into sumti with
`lo` and `ku`:

` [lo <nu {do speni mi} kei> ku] = "the event of our marriage"`

And can be incorporated into larger sentences:

`              ┌──fact selbri───┐`  
` mi djica [lo nu do speni mi kei ku]`  
`                └─────┬─────┘`  
`                 inner bridi`

` "I desire our marriage."`

### Properties

A third word, `ka` can also create a selbri from a bridi much like
`du'u` and `nu`:

` Pattern: ka BRIDI kei => SELBRI`

The bridi must contain at least one `ce'u` sumti:

`              ┌───────property selbri────────┐`  
` mi cnici [lo ka ce'u citka lo titnanba ku kei ku]`  
`                └────────────┬────────────┘`  
`                        inner bridi`

The `ce'u` has no meaning of its own. The selbri that receives the
property specifies what it refers to. In this case, it is `cnici` taking
the property as its x2.

The definition of `cnici` is:

` x1 is orderly/neat/ordered in property x2`

And so it is the x1, or `mi`, who is orderly in the eating of cookies.

` mi cnici [lo ka ce'u citka lo titnanba ku kei ku]`  
`  └───────┬────────┘`  
`     bound sumti`

` "I am orderly in the eating of cookies."`

The `ce'u` can appear anywhere in the inner bridi:

` do cinmo [lo ka la mam ku vajni ce'u kei ku]`  
`  └──────────────┬─────────────────┘`  
`            bound sumti`

` "You feel the emotion of Mother being important to you."`

Some selbri words make comparative statements:

` zmadu: x1 is more than x2 in property x3`

` do zmadu mi [lo ka ce'u citka lo titnanba ku kei ku]`  
`                   └────────────┬────────────┘`  
`                           inner bridi`

` do citka lo titnanba ku "is more than" mi citka lo titnanba ku`

` "You are more than me in the eating of cookies."`  
` "You eat more cookies than me."`

Numerous property relations exist within the Lojban lexicon.

### Relative Phrases

Additional information about a sumti can be provided by attaching a
bridi to it with `noi`:

` Pattern: SUMTI noi BRIDI ku'o => SUMTI'`

Similarly to the properties created with `ka`, `noi` bridi have a
stand-in word `ke'a`:

` ko penmi la rozgu ku noi mi prami ke'a ku'o`  
`                         └──────┬──────┘`  
`                           inner bridi`

` Meet Rose, who I love.`

The `noi` bridi is attached to `la rozgu ku` and so it is her to whom
`ke'a` refers to.

If the information is not merely incidental but nessecary to discern
which thing is being talking about `poi` can be used instead:

` ko penmi lo bruna ku poi mi prami ke'a ku'o`  
`                         └──────┬──────┘`  
`                           inner bridi`

` Meet the brother I love (compared to whichever I don't.)`

## Understanding Time

The basic tenses `pu`, `ca` and `ba` were covered previously but there
is a bit more to say about time.

### Basic Tenses

The tense for stating something is currently happening is `ca`:

` mi ca citka`  
`    ──`  
` "I am currently eating."`

Another way of stating this (which will be helpful later) is:

` "The present coincides with my eating."`

`              citka`  
`    ⇜┬──────────┼──────────┬⇝`  
`    Past       Now       Future`

How about the other tenses?

` mi pu pensi`  
`    ──`  
` "I was thinking."`

` "The past coincides with my thinking."`

`   pensi`  
`    ⇜├──────────┬──────────┬⇝`  
`    Past       Now       Future`

` do ba jimpe`  
`    ──`  
` "You will understand."`

` "The future coincides with your understanding."`

`                         jimpe`  
`    ⇜┬──────────┬──────────┤⇝`  
`    Past       Now       Future`

### Event Contours

All events have a "temporal extent" or lifetime. It is often useful to
describe the various events "within" an event. The ZAhO family of tenses
can be used for accessing
them:

`                                                      ╎ pu'o:  before`  
`pu'o      ═══════════╣  ╠════════════       ba'o      ╎ co'a:  the outset`  
`        co'a      de'a  di'a       co'u               ╎ de'a:  break`  
`                                                      ╎ di'a:  resumption`  
`          └───────────┬─────────────┘                 ╎ co'u:  finish`  
`                    co'i                              ╎ ba'o:  after`  
`                                                      ╎ co'i:  for the duration`

Like basic tenses, they modify a selbri to create a new one:

` Pattern: ZAhO SELBRI => SELBRI`

` mi <co'a `<citka>`> lo plise ku`  
`     ────`  
` "I'm starting to eat an apple."`

` mi pacna lo nu <co'u `<carvi>`> kei ku`  
`                 ────`  
` "I wish for it to finish raining."`

` ko <de'a `<tadni>`>`  
`     ────`  
` "Take a break from studying."`

` mi <pu'o `<sipna>`>`  
`     ────`  
` "Its before my bedtime."`

` mi <ba'o `<prami>`> do`  
`     ────`  
` "My loving you has passed.""`

### Tensed Contours

If no basic tense is provided, `ca` or present-tense is assumed:

` mi <ca <co'a `<citka>`> lo plise ku`  
`     ──  ────`  
` "I'm starting to eat an apple"`  
` "The present coincides with the start of my apple eating."`

`                citka`  
`                ╠═══╣`  
`                ┊`  
`    ⇜┬──────────┼──────────┬⇝`  
`    Past       Now       Future`

But how do the ZAhO contours interact with different CA tenses?

` mi <pu <pu'o `<sipna>`>>`  
`     ──  ────`  
` "It was before my bedtime."`  
` "The past coincides with the runup to my bedtime."`

`       sipna`  
`     ┊ ╠═══╣`  
`     ┊`  
`    ⇜┼──────────┬──────────┬⇝`  
`    Past       Now       Future`

` mi <ba <ba'o `<prami>`>> do`  
`     ──  ────`  
` "My loving you will have passed."`  
` "The future coincides with the aftermath of our love."`

`                    sipna`  
`                    ╠═══╣  ┊`  
`                           ┊`  
`    ⇜┬──────────┬──────────┼⇝`  
`    Past       Now       Future`

## Prepositions

Additional sumti places can be added to a bridi by importing them with
`fi'o`:

` Pattern: fi'o SELBRI SUMTI => SUMTI`

The x1 place of the specified selbri is added to the bridi and filled
with the specified sumti:

`                        ┌────────fi'o clause───────┐`  
` mi citka lo titnanba ku fi'o `<jukpa>` [la rozgu ku]`  
` "I'm eating the cookies baked by Rose"`

### Stage Additions

This can be understood in terms of the stage-play metaphor used before.
`fi'o` terms act as assistant directors adding additional
roles:

` STAGE:`  
`        mi    citka  lo titnanba ku  fi'o jukpa   la rozgu ku      <= actors in the play`  
`     [eater]    │       [meal]           │           [cook]        <= roles in the play`  
`        ├───────┼──────────┤             ├─────────────┤`  
`      role1  director    role2     asst. director  jukpa-role`

### SE Prepositions

Any selbri is compatible and that includes ones modified by SE:

` lo cinfo ku kalte fi'o se pilno lo kanla ku`  
` "The lion hunts with its eyes."`

` lo kalte ku cizda'u fi'o te jvinu lo se citka ku`  
` "The hunter is a monster from the perspective of the meal."`

### Spatial Prepositions

Some useful selbri for prepositions stating where the bridi takes place:

`  selbri    │ gloss`  
` ───────────┼──────────────`  
`  se zvati  │ located at`  
`  se jibni  │ located near`  
`  se nenri  │ located in`  
`  te ragve  │ across from`  
`  se gapru  │ above`  
`  se cpana  │ ontop of`  
`  se cnita  │ underneath`  
`  se sruri  │ surrounding`

### Temporal Prepositions

A few selbri useful for prepositions denoting when a bridi takes place:

`  selbri    │ gloss`  
` ───────────┼──────────────`  
`  tcika     │ at time`  
`  detri     │ on date`  
`  balvi     │ before`  
`  cabna     │ during`  
`  purci     │ after`

### Causal Prepositions

Some selbri useful for propositions explaining how a bridi came about:

`  selbri    │ gloss`  
` ───────────┼──────────────`  
`  mukti     │ motivated by`  
`  rinka     │ caused by`  
`  krinu     │ justified by`  
`  jalge     │ with result`

### BAI Prepositions

A small number of cmavo in the BAI family can be used for specifying
useful prepositions as a shortcut:

` Pattern: BAI SUMTI => SUMTI`

Just like `fi'o` prepositions each cmavo from the BAI family encodes a
particular sumti place:

`  selbri    │ BAI    │ gloss`  
` ───────────┼────────┼──────────────────`  
`  mukti     │ mu'i   │ motivated by`  
`  rinka     │ ri'a   │ caused by`  
`  krinu     │ ki'u   │ justified by`  
`  jalge     │ ja'e   │ with result`  
`  vanbi     │ va'o   │ under conditions`  
`  gasnu     │ gau    │ performed by`  
`  tadji     │ ta'i   │ with approach`  
`  catni     │ ca'i   │ by authority`  
`  cusku     │ cu'u   │ said by`  
`  se pilno  │ sepi'o │ using tool`

These can result in slightly more terse prepositional clauses:

`                  ┌─────BAI clause─────┐`  
` lo cinfo ku kalte sepi'o [lo kanla ku]`  
` "The lion hunts with its eyes."`

## Miscellaneous additions

### Indirect questions

The word `kau` in a fact "defuses" a preceding question word, and
focuses that whole fact on the would-be answer.

` Pattern: QUESTION_WORD kau => QUESTION_WORD`

`                          ┌────indirect question───┐`  
` la krili ku kucli lo du'u ma kau finti lo pemci ku kei ku`  
`                           ──────`  
` "Crystal is curious as to who invented the poem."`

`                 ┌──indirect question─┐`  
` mi djuno lo du'u do cliva mu'i ma kau kei ku`  
`                                ──────`  
` "I know why you left."`

`                    ┌─indirect question─┐`  
` mi na morji lo du'u xu kau  misno kagni kei ku`  
`                     ──────`  
` "I don't remember whether or not it was a famous company."`

`                    ┌──indirect question──┐`  
` mi na jimpe lo du'u lo nabmi ku mo kau mi kei ku`  
`                                 ──────`  
` "I don't understand what the issue has to do with me."`

(If we don't add `kau`, the whole sentence is simply a complex question
asking what fills `ma`, as before:)

` la krili ku kucli lo du'u ma finti lo pemci ku kei ku.`  
`                           ──`  
` "Who is it that Crystal is curious about them inventing the poem?"`

### Elliptical words

A couple of the classes of words we've handled have an "elliptical"
member, with carry an intentionally unspecified meaning.

Using one of these means: "I assume the listener will know what I mean,
so I don't have to specify exactly."

Think of words like "you-know-what", "thingy", et
cetera.

`  word    │ type   │ gloss`  
` ─────────┼────────┼──────────────────────────`  
`  zo'e    │ SUMTI  │ unspecified argument (equivalent to not filling a place)`  
`  co'e    │ SELBRI │ unspecified relation`  
`  do'e    │ BAI    │ unspecified preposition`  
`  ge'e    │ UI     │ unspecified emotion`

These words are very useful when you don't know exactly which word to
use, but it doesn't matter.

` mi ba cusku zo'e la rozgu ku`  
`             ────`  
` "I'll tell Rose."  (unspecified x2)`

` .au do co'e`  
`        ────`  
` "I want you to."  (unspecified predicate)`

` ciska do'e lo latmo lerfu ku`  
`       ────`  
` "Write (in/with/…) Latin characters."`

` ge'e mi cliva`  
` ────`  
` "Eh, I'm leaving."  (unspecified emotion)`

### Some event involving…

There is also a word, `tu'a`, for building facts, events, or properties
that involve a sumti in some unspecified manner.

` Pattern: tu'a SUMTI => SUMTI`

(Essentially, `tu'a SUMTI` is short for `lo (du'u/nu/ka) SUMTI co'e kei
ku`.)

` steba: x1 is frustrated about x2 (fact/event).`  
` `  
` mi steba lo nu stodi gunka lo jibri ku ja'e lo mabla ku kei ku`  
`          ─────────────────────────────────────────────────────`  
` "I'm frustrated by steadily working my job with crappy results."`  
` `  
` mi steba tu'a lo jibri ku`  
`          ────────────────`  
` "I'm frustrated about my job."`

` lerci: x1 (event) happens late by x2's standards.`  
` `  
` lo nu lo trene ku darca lo tcana ku kei ku lerci`  
` ──────────────────────────────────────────`  
` "The train arriving at the station happens late."`  
` `  
` tu'a lo trene ku lerci`  
` ────────────────`  
` "The train is late."`

### Sumti raising

Let's take a closer look at the last example.

In Lojban, we can't say something like `lo trene ku lerci`. The only
thing that can be late is some event in time, and a train is not an
event\!

So, we use `tu'a` to "wrap" `lo trene ku` in an abstraction. (Doing this
is sometimes called *sumti raising*.)

There is another word to help us do the same thing, namely `jai`.

` Pattern: jai SELBRI => SELBRI`

Instead of wrapping a sumti, it modifies a selbri's meaning to have a
"wrapped" x1. These two are equivalent:

`         x1   jai SELBRI   x2 x3 x4 …`  
` ≡ (tu'a x1)      SELBRI   x2 x3 x4 …`

This becomes more useful once we combine it with
`lo`.

` nabmi      = x1 (nu) poses a problem to x2.`  
` jai nabmi  = x1 (thing) is problematic to x2; as in, something abstract involving x1 is a problem to x2.`

` lo nabmi ku      = a problem (event).`  
` lo jai nabmi ku  = something problematic (any type).`

### Dropping terminators

Those `ku`s and `kei`s are really starting to stack up. You can often
omit them. For example at the end of a bridi:

`   mi troci lo nu darxi lo bolci ku kei ku`  
` → mi troci lo nu darxi lo bolci`  
`   "I try to hit the ball."`

Or at the end of an inner bridi:

`        ┌───inner bridi───┐`  
`   lo nu ponse lo fonxa ku kei ku xlali lo verba ku`  
` → lo nu ponse lo fonxa    kei ku xlali lo verba`  
`   "Owning a phone is bad for kids."`

You can drop `ku` if it is followed by a *neighboring* sumti in the
current bridi:

`   mi canja lo jemna ku lo solji ku do`  
` → mi canja lo jemna    lo solji    do`  
`   "I trade gems in return for gold with you."`

There are other cases where it's possible, but they're not as clear-cut.
