# YOconlang: function-word blocks VV · CV · VC · VCV
# YOconlang: блоки служебных слов VV · CV · VC · VCV

> **Status / Статус:** proposal v3, not final. / предложение v3, не окончательная версия.
> Generated from the v3 spreadsheet; every form below is checked for uniqueness and completeness. / Собрано из таблицы v3; уникальность и полнота форм проверены скриптом.

## 1. Overview / Обзор

**EN.** Function words are built from the 16 letters of the YOalphabet: 5 vowels (`o a e u i`) and 11 consonants (`t n l v b s h p m k j`).
The template of a word (V = vowel, C = consonant) tells you what kind of word it is.

**RU.** Служебные слова строятся из 16 букв YOalphabet: 5 гласных (`o a e u i`) и 11 согласных (`t n l v b s h p m k j`).
Шаблон слова (V = гласная, C = согласная) подсказывает, какого типа это слово.

| Template | Slots | Used | Free | Role (EN / RU) |
|---|---|---|---|---|
| VV | 25 | 23 | 2 (`ai`, `ao`) | discourse, logic, clause markers / дискурс, логика, маркеры придаточных |
| CV | 55 | 55 | 0 | numerals and grammatical particles / числа и грамматические частицы |
| VC | 55 | 55 | 0 | pronouns and the correlative grid / местоимения и таблица коррелятов |
| VCV | 275 | 27 | 248 | rare and derived words, growth reserve / редкие и производные слова, резерв |
| CVV | 275 | 0 | 275 | untouched reserve / нетронутый резерв |

## 2. Design rules / Принципы

1. **Frequency → length. / Частота → длина.** Two-letter templates hold frequent words (tiers A and B). Rare and new words go to VCV. «this» is more frequent than «that», so «this» is 2 letters and «that» is 3. / В двухбуквенных шаблонах частые слова (A и B), редкие и новые идут в VCV. «Этот» чаще «того», поэтому «этот» из двух букв, а «тот» из трёх.
2. **Systematic grids. / Системные сетки.** VC: vowel = series, consonant = column. CV: consonant = group, vowel = member. VV: first vowel = group. / VC: гласная = ряд, согласная = столбец. CV: согласная = группа, гласная = член группы. VV: первая гласная = группа.
3. **Opposites stay apart. / Противоположности разнесены.** Opposite or paired meanings avoid the close vowel pairs `o/u` and `e/i` (e.g. past `to` vs future `te`, in `li` vs from `lu`, all `e-` vs some `u-`). / Противоположные и парные значения не ставятся на близкие гласные `o/u` и `e/i`.
4. **VCV rule. / Правило VCV.** Different vowels = a VC word + a modifier vowel (`a·C·u` = «far» form of the a- series). Equal vowels = an independent particle; the first vowel gives the area: `o` number and degree, `i` space and time, `a` reference and difference, `e` speech and logic, `u` focus. / Разные гласные = VC плюс гласная-модификатор (`a·C·u` = «дальняя» форма ряда a-). Одинаковые гласные = самостоятельная частица; первая гласная задаёт область: `o` число и степень, `i` пространство и время, `a` ссылка и различие, `e` речь и логика, `u` фокус.
5. **Frequency tiers / Уровни частоты.** `A` very frequent, `B` common, `C` rare, `—` not rated (numerals). Estimated from general usage, not from a corpus. / `A` очень частые, `B` обычные, `C` редкие, `—` не оцениваются (числа). Оценка по общему опыту, не по корпусу.
6. **Frozen. / Заморожено.** The 16 digit names (`jo ka me ti pu no la ve hi bu so ha pe mi ku ja`) and the scale words `sa se su si` are unchanged; the names of 11 consonant letters equal digit names. / Названия 16 цифр и масштабы `sa se su si` не менялись; названия 11 букв-согласных совпадают с названиями цифр.

## 3. VV: discourse and logic / дискурс и логика

| Form | English | Русский | Freq | Note / Примечание |
|---|---|---|---|---|
| **Answers and number mode / Ответ и режим чисел** | | | | |
| `oo` | number mode (digits follow) | режим чисел | — |  |
| `oa` | yes | да | A |  |
| `ou` | no (answer) | нет (ответ) | A |  |
| `oe` | maybe | возможно | B |  |
| `oi` | passive voice marker | пассив (маркер залога) | A |  |
| **Clauses and mood / Придаточные и наклонение** | | | | |
| `aa` | that (conjunction: "said that…") | что (союз: «сказал, что…») | A |  |
| `au` | in order to (purpose) | чтобы (цель) | A |  |
| `ae` | would (irrealis, conditional) | бы (ирреальность, условное) | A |  |
| **Question and logic / Вопрос и логика** | | | | |
| `ee` | question marker | вопрос | A |  |
| `ea` | and | и | A |  |
| `eu` | or | или | A |  |
| `ei` | if | если | A |  |
| `eo` | although (concession) | хотя (уступка) | B |  |
| **Address and linking / Обращение и связь** | | | | |
| `ii` | address (vocative) | обращение | B |  |
| `io` | then | то | B |  |
| `ia` | make, cause | заставить | B |  |
| `ie` | there is, exists | есть, существует | A |  |
| `iu` | identity (is, equals) | тождество | A |  |
| **Negation and focus / Отрицание и уточнение** | | | | |
| `uu` | not | не | A |  |
| `ua` | again | снова | B |  |
| `ue` | only | только | B |  |
| `uo` | already | уже | A | was: even / было: даже |
| `ui` | still, yet | ещё, всё ещё | A | was: otherwise / было: иначе |

**Free / Свободно:** `ai`, `ao`.
**Notes / Примечания.** EN: punctuation marks get their own symbols, so the former words for full stop, quotes, colon and «etc.» (`oi aa au ae ao`) were reused for new frequent words. RU: знаки препинания получают отдельные символы, поэтому прежние слова для точки, кавычек, двоеточия и «и так далее» (`oi aa au ae ao`) отданы новым частым словам.

## 4. CV: numerals and particles / числа и частицы

| Form | English | Русский | Freq | Note / Примечание |
|---|---|---|---|---|
| **Digits / Цифра** | | | | |
| `jo` | 0 | 0 | — |  |
| `ka` | 1 | 1 | — |  |
| `me` | 2 | 2 | — |  |
| `ti` | 3 | 3 | — |  |
| `pu` | 4 | 4 | — |  |
| `no` | 5 | 5 | — |  |
| `la` | 6 | 6 | — |  |
| `ve` | 7 | 7 | — |  |
| `hi` | 8 | 8 | — |  |
| `bu` | 9 | 9 | — |  |
| `so` | 10 (hex digit) | 10 (шестнадцатеричная цифра) | — |  |
| `ha` | 11 (hex digit) | 11 (шестнадцатеричная цифра) | — |  |
| `pe` | 12 (hex digit) | 12 (шестнадцатеричная цифра) | — |  |
| `mi` | 13 (hex digit) | 13 (шестнадцатеричная цифра) | — |  |
| `ku` | 14 (hex digit) | 14 (шестнадцатеричная цифра) | — |  |
| `ja` | 15 (hex digit) | 15 (шестнадцатеричная цифра) | — |  |
| **Scale / Масштаб** | | | | |
| `sa` | decimal point | десятичная точка | — |  |
| `se` | 10² (hundreds) | 10² (сотни) | — |  |
| `su` | 10³ (thousands) | 10³ (тысячи) | — |  |
| `si` | 10⁶ (millions) | 10⁶ (миллионы) | — |  |
| **Tense / Время** | | | | |
| `to` | past | прошедшее | A |  |
| `ta` | present, ongoing | идёт сейчас | A |  |
| `te` | future | будущее | A |  |
| `tu` | completed (perfect) | завершено | A |  |
| **Place / Место** | | | | |
| `li` | in, on | в, на | A |  |
| `le` | to | к | A |  |
| `lu` | from | из | A |  |
| `lo` | through | через | A |  |
| **Modality / Модальность** | | | | |
| `na` | want | хочу | A |  |
| `ne` | can, may | могу, можно | A |  |
| `nu` | must | должен | A |  |
| `ni` | command (imperative) | повеление | A |  |
| **Degree / Степень** | | | | |
| `pa` | much, many | много | A |  |
| `po` | little, few | мало | A |  |
| `pi` | very | очень | A |  |
| **Roles / Роли** | | | | |
| `ba` | for | для | A |  |
| `be` | with | с | A |  |
| `bi` | by means of | посредством | A |  |
| `bo` | of, belonging to | принадлежность («из», «у») | A |  |
| **Comparison / Сравнение** | | | | |
| `va` | more | более | B |  |
| `vi` | less | менее | B |  |
| `vu` | most | самый | B |  |
| `vo` | than, as | чем, как | B |  |
| **Subordination / Подчинение** | | | | |
| `ki` | because | потому что | A |  |
| `ko` | therefore | поэтому | B |  |
| `ke` | which, who (relative) | который | A |  |
| **Phase / Фаза** | | | | |
| `he` | begin | начать | B |  |
| `ho` | continue | продолжать | B |  |
| `hu` | finish | закончить | B |  |
| **Sentence linking / Связь предложений** | | | | |
| `je` | but | но | A |  |
| `ju` | also, too | тоже | A |  |
| `ji` | about, concerning | о, касательно | B |  |
| **Word class / Класс слова** | | | | |
| `ma` | adjective marker | прилагательное | A |  |
| `mo` | adverb marker | наречие | B |  |
| `mu` | plural marker | множественное число | A |  |

**Notes / Примечания.** EN: digits stay in CV for now; a second layer for numerals is under consideration. Ordinals use the VCV particle `oho` (`ka oho` = «first»). RU: цифры пока остаются в CV; второй слой для числительных обсуждается. Порядковые числа строятся частицей `oho` (`ka oho` = «первый»).

## 5. VC: pronouns and correlatives / местоимения и коррелятивы

**EN.** The `i-` series holds personal pronouns. Series `a-` (demonstrative), `o-` (interrogative), `e-` (universal), `u-` (indefinite) share one column order: `s n l t v b h k m p j` = person, thing, place, time, manner, reason, quantity, kind, possessive, choice, degree.
**RU.** Ряд `i-` содержит личные местоимения. Ряды `a-` (указательные), `o-` (вопросительные), `e-` (всеобщие), `u-` (неопределённые) имеют один порядок столбцов: `s n l t v b h k m p j` = лицо, вещь, место, время, образ действия, причина, количество, качество, принадлежность, выбор, степень.

| Form | English | Русский | Freq | Note / Примечание |
|---|---|---|---|---|
| **Personal / Личные** | | | | |
| `im` | I | я | A |  |
| `it` | you (sg.) | ты | A |  |
| `in` | he, she | он, она | A |  |
| `il` | we (incl. you) | мы (с тобой) | A |  |
| `is` | we (excl. you) | мы (без тебя) | A |  |
| `ik` | you (pl.) | вы | A |  |
| `iv` | they | они | A |  |
| `ib` | oneself (reflexive) | себя | B |  |
| `ip` | each other (reciprocal) | друг друга | B |  |
| `ij` | it | оно | B |  |
| `ih` | one, someone (generic) | некто (обобщённо) | B | also the name of letter I / также название буквы I |
| **Demonstrative (a-) / Указательные** | | | | |
| `as` | this (person) | этот (лицо) | A |  |
| `an` | this (thing) | это (вещь) | A |  |
| `al` | here | здесь | A |  |
| `at` | now | сейчас | A |  |
| `av` | so, thus | так | A |  |
| `ab` | for this reason | потому | C |  |
| `ah` | this much | столько | C |  |
| `ak` | such | такой | B | also the name of letter A / также название буквы A |
| `am` | of this (possessive) | этого (принадлежность) | C |  |
| `ap` | this one of | этот из | C |  |
| `aj` | to this extent | настолько | C |  |
| **Interrogative (o-) / Вопросительные** | | | | |
| `os` | who | кто | A |  |
| `on` | what | что | A |  |
| `ol` | where | где | A |  |
| `ot` | when | когда | A |  |
| `ov` | how | как | A |  |
| `ob` | why | почему | A |  |
| `oh` | how many, how much | сколько | B |  |
| `ok` | what kind of | какой | A |  |
| `om` | whose | чей | B |  |
| `op` | which of | который из | C |  |
| `oj` | to what extent | насколько | C | also the name of letter O / также название буквы O |
| **Universal (e-) / Всеобщие** | | | | |
| `es` | everyone | все | A |  |
| `en` | everything | всё | A |  |
| `el` | everywhere | везде | B |  |
| `et` | always | всегда | B |  |
| `ev` | in every way | всяко | C |  |
| `eb` | for any reason | по любой причине | C |  |
| `eh` | all (counted) | все (по счёту) | C |  |
| `ek` | every kind of | всякий | B |  |
| `em` | of all (possessive) | всех (принадлежность) | C | also the name of letter E / также название буквы E |
| `ep` | each | каждый | B |  |
| `ej` | completely | полностью | B |  |
| **Indefinite (u-) / Неопределённые** | | | | |
| `us` | someone | кто-то | A |  |
| `un` | something | что-то | A |  |
| `ul` | somewhere | где-то | B |  |
| `ut` | sometime | когда-то | B |  |
| `uv` | somehow | как-то | B |  |
| `ub` | for some reason | почему-то | C |  |
| `uh` | several | несколько | A |  |
| `uk` | some kind of | какой-то | A |  |
| `um` | someone's | чей-то | C |  |
| `up` | one of | один из | C | also the name of letter U / также название буквы U |
| `uj` | partly | отчасти | C |  |

**Notes / Примечания.**
- EN: negation is the prefix `uu`: `uu us` = «nobody». The possessive of a pronoun is `bo` + pronoun: `bo im` = «my». «Without» = `uu be`. «Until» = `ipi` + `ke`.
- RU: отрицание это приставка `uu`: `uu us` = «никто». Принадлежность у местоимения строится как `bo` + местоимение: `bo im` = «мой». «Без» = `uu be`. «Пока не» = `ipi` + `ke`.
- EN: the five forms `oj ak em up ih` are also the names of the vowel letters. RU: пять форм `oj ak em up ih` также являются названиями букв-гласных.
- EN: in this version the interrogative series moved from `e-` to `o-` and the universal series from `o-` to `e-` (mnemonic: `e` = every), so «all» and «some» no longer differ by a single close vowel. RU: в этой версии вопросительный ряд перенесён с `e-` на `o-`, а всеобщий с `o-` на `e-` (мнемоника: `e` = every), чтобы «все» и «кто-то» не различались одной близкой гласной.

## 6. VCV: derived and rare words / производные и редкие слова

| Form | English | Русский | Freq | Note / Примечание |
|---|---|---|---|---|
| **Far demonstratives (a·C·u) / Дальние указательные (a·C·u)** | | | | |
| `asu` | that (person) | тот (лицо) | A | a-series + u (far) / ряд a- + u (далеко) |
| `anu` | that (thing) | то (вещь) | A | a-series + u (far) / ряд a- + u (далеко) |
| `alu` | there | там | B | a-series + u (far) / ряд a- + u (далеко) |
| `atu` | then (at that time) | тогда | B | a-series + u (far) / ряд a- + u (далеко) |
| `amu` | of that (possessive) | того (принадлежность) | C | a-series + u (far) / ряд a- + u (далеко) |
| **Number and degree (o·C·o) / Число и степень (o·C·o)** | | | | |
| `oho` | ordinal particle (-th) | порядковая частица («-й»: ka oho «первый») | B | h = quantity column / h = столбец количества |
| `oto` | too (excessively) | слишком | B | t = too / t = too |
| `oso` | enough | достаточно | C | s = sufficient / s = sufficient |
| `omo` | almost | почти | C | m = almost / m = almost |
| `opo` | approximately, about | около, приблизительно | C | p = approx. / p = approx. |
| `ovo` | times (multiplicative) | раз (кратность) | C | v = vez, times / v = vez, раз |
| `oko` | half | половина | C | arbitrary / произвольно |
| **Space and time (i·C·i) / Пространство и время (i·C·i)** | | | | |
| `ipi` | before | до (время) | B | p = pre- / p = pre- |
| `isi` | after | после (время) | B | s = subsequent / s = subsequent |
| `ili` | at, near | у, около (место) | B | l = locus / l = locus |
| `ihi` | above | над | C | h = high / h = high |
| `ibi` | below | под | C | b = below / b = below |
| `imi` | between | между | B | m = middle / m = middle |
| `iki` | against | против | C | k = contra / k = contra |
| **Reference and difference (a·C·a) / Ссылка и различие (a·C·a)** | | | | |
| `ala` | other, another | другой | B | l = alter / l = alter |
| `asa` | same | тот же, такой же | B | s = same / s = same |
| `ama` | aforementioned | упомянутое выше | C | m = mentioned / m = mentioned |
| **Speech and logic (e·C·e) / Речь и логика (e·C·e)** | | | | |
| `epe` | for example | например | B | p = per exemplum / p = per exemplum |
| `ete` | that is (i.e.) | то есть | B | t = that is / t = that is |
| `eve` | either … or | либо…либо | C | v = Latin vel / v = лат. vel |
| **Focus (u·C·u) / Фокус (u·C·u)** | | | | |
| `uvu` | even | даже | C | v = even / v = even |
| `ulu` | otherwise | иначе | C | l = else / l = else |

**Plural of demonstratives / Множественное число указательных:** `mu` after the word / `mu` после слова.

## 7. Open points / Открытые вопросы

- EN: the README examples (e.g. the UDHR article 1 translation) still use the old forms (`KE` «and», `HA` «about», `TO`/`TU`) and must be rewritten. RU: примеры в README (например, перевод статьи 1 Всеобщей декларации прав человека) ещё используют старые формы (`KE` «и», `HA` «относительно», `TO`/`TU`) и должны быть переписаны.
- EN: consonants in VCV are mnemonic and can be replaced freely; `oko` has no mnemonic. RU: согласные в VCV подобраны по мнемонике и могут быть заменены; у `oko` мнемоники нет.
- EN: 15 rare cells of the VC grid (tier C) stay in VC for regularity and can be moved to VCV if slots run out. RU: 15 редких ячеек сетки VC (уровень C) остаются в VC ради регулярности и могут быть перенесены в VCV, если слотов не хватит.
