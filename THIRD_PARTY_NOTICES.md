# Learning content and third-party notices

Hibi's application code and its learning data are separate works. The package is private; no license grant for the application code is implied by the licenses of its data.

## Dictionary, kanji and level annotations

The bundled catalogue is adapted from [OpenJLPT](https://github.com/evanclan/OpenJLPT), revision recorded in `src/data/content-manifest.json`. The adapted catalogue is distributed under **CC BY-SA 4.0**. The license is included in `public/licenses/OpenJLPT-LICENSE.txt` and in the built app.

OpenJLPT incorporates the Japanese and English components of **JMdict** and **KANJIDIC2**, copyright James William BREEN and the Electronic Dictionary Research and Development Group. See the [EDRDG documentation and license](https://www.edrdg.org/edrdg/licence.html). The derived dictionary data remains CC BY-SA 4.0. Source identifiers, readings, meanings and original-level annotations are preserved in the preparation source; derived entries use stable upstream IDs.

N5 is a focus annotation, not an official published vocabulary list. The course contains 674 entries annotated N5 upstream, plus 326 everyday additions originally annotated N4. Its 100-kanji target also includes separately labeled supplements. Do not describe it as an official JLPT syllabus or promise a passing result from a word count.

## Sentences

Hibi's own beginner examples and exercises are original application content. Reference examples originate from [Tatoeba](https://tatoeba.org/) through OpenJLPT. Each reference example links to its original sentence page, where its contributor and license can be found. Tatoeba text is generally available under CC BY 2.0 France; honor the license and contributor attribution on the linked entry. Reference examples are labeled because they may contain grammar beyond the current unit. They are not copied JLPT test questions.

## Illustrations and user-selected images

Bundled illustrations are **OpenMoji**, by the OpenMoji contributors, under **CC BY-SA 4.0**. Full license: `public/licenses/OpenMoji-LICENSE.txt`. Each catalogue illustration retains its author, original source link and license. Illustrations are displayed without modifying their artwork. [OpenMoji](https://openmoji.org/).

Images selected through Wikimedia Commons retain their own author, source page and license in the learner's image-choice event. The app accepts CC BY, CC BY-SA, CC0 and public-domain results, fits the complete image, and caches selected files locally. A search result is a candidate; the learner must verify that it actually conveys the intended word meaning.

No NHK recordings or game artwork are included. No AI-generated word pictures are included.

## Software and font

The desktop shell uses Electron. Interface: React, Lucide, Vite, Barlow Condensed (SIL Open Font License), and WanaKana. Scheduling: ts-fsrs. Local storage: SQL.js / SQLite. Cloud integration: Firebase. Input validation: Zod. Japanese tokenization used when preparing content: Kuromoji. Their package license files remain with their respective distributions; exact versions are locked in `package-lock.json`.
