# GitHub Pages发布包 · 2026-10-26

本包不包含VOA第21、43、45课完整原文／MP3、Irodori个人副本、未选候选录音、学习备份或凭据。其余素材保留既有来源与逐文件署名；技术打包不构成逐轨版权终审或教师签审。以下是项目历次来源记录，历史“本地副本”描述不表示这些文件包含于本包。

# Third-party data notices

## ECDICT

English word entries, phonetics, Chinese translations, part-of-speech metadata and exam tags used by generated word banks are derived from [ECDICT](https://github.com/skywind3000/ECDICT), Copyright © 2025 Linwei, under the MIT License. A copy of the upstream license is available in the linked repository.

## WordNet

Example sentences for generated word banks are derived where available from the Princeton WordNet database, distributed through the `wordnet-db` package under the WordNet license. WordNet is provided without warranty.

Generated word-bank JSON files retain `source: "ecdict"` on every imported record. Original demonstration entries retain `source: "original"`.

## Tatoeba

English–Mandarin Chinese and Japanese–Mandarin Chinese aligned example sentences are selected from the official [Tatoeba downloads](https://tatoeba.org/en/downloads), released under CC BY 2.0 FR unless an individual sentence is marked CC0. Generated records preserve the source sentence id as `sourceId`; the learning page displays that id and the license beside each matched example.

Question-bank vocabulary exercises derived from these examples also keep the sentence id, source link, license and attribution. Their prompts, distractors and explanations are original to YYYYQの学习工作台.

## Reading source material

Selected English reading passages are adapted from openly reusable source material. Each article stores and displays its own source URL, license, attribution and adaptation note.

- U.S. Geological Survey and NASA source concepts are taken from identified U.S. Government pages marked public domain or covered by the agencies' public reuse guidance. Third-party images and media are not included.
- Our World in Data articles are reused under CC BY 4.0 with the named authors and source page credited on the article screen.
- All questions, answer choices, Chinese vocabulary notes and teaching explanations are original to YYYYQの学习工作台.

## VOA Learning English — Let’s Learn English Level 1

Units 1–10 contain VOA's Conversation transcripts and original MP3 audio, downloaded from links on the official lesson pages on 2026-10-09. Adjacent lines may be grouped into learning paragraphs and non-spoken stage directions omitted. Source: VOA Learning English, https://learningenglish.voanews.com. Attribution remains visible in the reading and listening screens.

VOA states that its Learning English texts and MP3s are public domain and may be reprinted for educational and commercial purposes with credit: https://learningenglish.voanews.com/p/6861.html. Third-party agency media are excluded. No third-party images, videos or quizzes have been imported. Chinese translations, vocabulary notes, grammar commentary and comprehension questions are independently written for this project.

The source pages and original MP3 URLs are recorded in `src/data/voaFoundation.ts` and `src/data/voaFoundationExpansion.ts`. Local recordings are in `public/audio/voa/lesson-01.mp3` through `lesson-10.mp3`. Full and user-defined A–B clips play original recordings. Learners may associate a manually selected clip with a sentence in their current listening draft. Unmapped sentences use explicitly labelled synthesized speech; no verified automatic alignment is claimed.

## JMdict and OpenJLPT

The generated Japanese N5–N1 word bank is imported from [OpenJLPT](https://github.com/evanclan/OpenJLPT), which links and validates vocabulary entries against JMdict from the Electronic Dictionary Research and Development Group (EDRDG). The redistributed word-bank data is licensed under CC BY-SA 4.0. Example sentence records retain their Tatoeba sentence IDs when provided by the source dataset.

The current JLPT does not publish an official fixed vocabulary list. Level labels in this project are therefore community learning approximations supplied by OpenJLPT, not claims about an official JLPT syllabus.

## Japanese–Chinese Thesaurus

Simplified Chinese meanings matched to the Japanese N5–N1 word bank are selected from [Japanese-Chinese-thesaurus](https://github.com/lxl66566/Japanese-Chinese-thesaurus), released under The Unlicense. The project keeps the original JMdict English gloss beside the matched Chinese learning meaning and falls back to English where no exact Japanese headword match is available.
# Public tutorial import — 2026-10-13

VOA Learning English, Let’s Learn English Level 1: all 52 Conversation transcripts and corresponding official MP3 files locally imported with source attribution. Official use terms: https://learningenglish.voanews.com/p/6861.html . No third-party illustrations, videos or official quizzes imported. This describes local import, not blanket clearance of embedded third-party works: lesson 21 contains a credited Richard M. Jones song and lesson 45 contains a credited Woody Guthrie song; their lyrics and full recordings require separate publication-rights review before public distribution. Lesson 43's sung ending and other recordings also require music-rights review; the local-import manifest is not an exhaustive rights audit.

Irodori Japanese for Life in Japan, Starter: complete 18-lesson catalog; lessons 1–4 PDF and 100 MP3 tracks copied for personal local study only. Copyright © The Japan Foundation Japanese-Language Institute, Urawa / original rights owners. Terms: https://www.irodori.jpf.go.jp/en/privacy.html . These are NOT blanket open-source assets; local copies live outside public/dist and are excluded from default Git tracking. See PUBLIC_TUTORIALS.md before any publication or commercial reuse.

## Reviewed open-practice samples — 2026-10-14

- **Bilingual English Grammar Courseware**, Adam Wang, https://github.com/Arikimizord/english-grammar-bilingual-slides, revision `862062deafccfbb0aa1a95e5c77300f31c4226c1`: selected content from `content/nouns.py` and `content/articles.py`, **CC BY-SA 4.0**. Two supplementary lessons and 12 exercises are adapted, with added translations/options and corrected overgeneralized rules. No remote Python or AGPL presentation template was executed or copied. Adapted teaching data remains CC BY-SA 4.0, separable from application code, downloadable at `/open-materials/grammar-sample.json`.
- **SQuAD 1.1**, Pranav Rajpurkar, Jian Zhang, Konstantin Lopyrev, Percy Liang and annotators; passages by Wikipedia contributors, https://rajpurkar.github.io/SQuAD-explorer/: three passages (Teacher, Amazon_rainforest, Steam_engine), nine original questions and original answer spans, **CC BY-SA 4.0**. Choice options, Chinese overview and explanations are project adaptations, not original multiple-choice questions or CET exam items. Adapted data remains CC BY-SA 4.0, downloadable at `/open-materials/squad-sample.json`. Conflicting annotations in an Apollo sample were rejected; historical article data is not claimed to be current statistics.
- License text: `/licenses/open-practice-CC-BY-SA-4.0.txt`. Source URLs and SHA-256 hashes: `/open-materials/open-practice-manifest.json`; corresponding source records also live under `src/data/imported`.
- **VOA lessons 11–20** use already imported full human recordings and selected original Conversation excerpts. Chinese core-excerpt translations, Chinese teaching notes, 30 comprehension checks and 20 grammar checks are original. No claim of complete Chinese translation or verified automatic timestamps is made. A total of 58 comprehension checks from lessons 1–20 are reused as separately identified listening-bank entries; this does not create 58 additional distinct exercises.
- **Common Voice** audio has not been imported. The reviewed Scripted Speech 26.0 British English release is CC0-labelled but also includes a no-rehosting condition: https://mozilladatacollective.com/datasets/cmrt6zrob000zmm07yqwjlpwi . Clarify actual download and redistribution scope before bundling any such data. Do not obtain it through unofficial mirrors or silently replace it with synthesized speech.

### CET6 listening-method companions — 2026-10-15

Six existing unmodified VOA recordings are now connected to CET6 method lessons and 25 independent checks: The Interview (Level 2), Will It Float? (Level 2), Seeking Support at Emory University (Pete Musto), Train Your Brain to Think in English (Alice Bryant), Avoid Ineffective Study Methods and Improve Your Knowledge of English Words by Testing Yourself (John Russell). Plain-text attribution: VOA Learning English / Voice of America / voanews.com. Source dates, URLs, original MP3 URLs, hashes, selection and exclusions are documented in CET6_LISTENING_SOURCES.md and src/data/imported/cet4-human-audio.json. The pre-existing cet4-human directory name is retained; no new recording or speed modification was made.

Selection relies on [VOA’s terms](https://learningenglish.voanews.com/p/5374.html) for VOA-produced material, not third-party licensed works. No photos, videos, dictionary definitions or official quizzes were imported into this batch. Apple audio was excluded from the CET6 whitelist after its dictionary appendix and a transcript/audio mismatch were identified. Authored Chinese teaching, summaries and 73 checks (48 teaching + 25 independent) are not official VOA content or a CET6-equivalent paper. Machine recognition and browser playback verification do not establish independent human listening, music clearance, legal clearance across jurisdictions or difficulty calibration. Public-release checks for third-party components remain required; earlier Level 1 / Irodori restrictions are unchanged.

### Latest teaching review — 2026-10-15

- VOA chapters 31–44 and 46–52: 63 legacy comprehension checks retain their prompts, options, answer indices and IDs, with authored explanations; 21 original checks append after them, evidenced in unchanged selected Conversation excerpts. Forty-two explicit source examples and forty-two legacy grammar checks have aligned teaching and per-option analysis. Across all 50 supported chapters there are now 199 distinct comprehension checks; listening/reading mirrors are not independent new exercises. No new recordings, lyrics, source excerpts, verified timestamps or human-audio-review claims were added. Chapters 21/45 remain unsupported pending separate credited-song review, and chapter 43's full audio still requires music-rights review. Existing local source files remain in the default public build, which is NOT thereby cleared for public distribution. Earlier batch counts below are historical.

### Expansion batch — 2026-10-14

- VOA chapters 22–30 review: twenty-seven legacy checks have specific authored explanations with unchanged prompts/options/answer positions; nine authored checks appended, all evidenced within the existing selected Conversation excerpts. Eighteen explicit source examples and eighteen legacy grammar checks aligned. The translation of “read the questions” now means reading them, not automatically answering them. Cumulative 50 chapters / 178 distinct comprehension checks; 29 reviewed chapters contain 115 checks. No media or human-reviewed timestamps added. Medical, game, driving and price scenes remain language material, not real-world recommendations. Existing pending music-rights boundaries remain unchanged; earlier counts below are historical.

- VOA chapters 11–20 teaching review: thirty legacy comprehension explanations revised while retaining original prompts/options/answers; ten original checks added, with evidence in already selected Conversation excerpts. Twenty explicit grammar examples now align with the teaching points, and twenty legacy grammar checks have authored per-option explanations. One Bangladeshi nationality translation corrected. Cumulative 50 supported chapters / 169 distinct comprehension checks, with 79 in the first twenty chapters; listening/reading mirrors are not additional independent exercises. Existing recordings and pending rights review remain unchanged. Chapter 18 is fictional story material, not verified real news; chapter 20's job/income remarks are not employment or earnings guarantees. No additional media or human-reviewed timestamps were introduced.

- Further comprehension refinement: chapters 4–10 retain all 21 legacy prompts/options/answer indices, with more specific authored explanations and source evidence. Seven new original checks cover event order, reference, spatial relations, response correction, polite postponement, temperature-unit clarification and route sequencing. Cumulative supported coverage: 50 chapters / 159 distinct comprehension questions; first ten chapters contain 39 checks. Listening/reading mirrors are not extra distinct exercises. No new media was imported, and no new human-reviewed audio timestamps or publication clearance are claimed. Earlier entries below retain their historical counts.

- Comprehension quality pilot: six legacy explanations revised without changing prompts/options/answers; four new authored questions appended across VOA chapters 1–3 (response reference, event order, pronoun reference and cause). Cumulative 50 supported chapters / 152 distinct comprehension questions, mirrored across listening and reading rather than double-counted. New checks retain verbatim Conversation evidence and are not official VOA quizzes or exam questions. Existing recording rights and pending music review are unchanged; no new human-audited timestamps are claimed.

- Final VOA auxiliary batch: lessons 41–44 and 46–52, eleven Chinese supplementary lessons, 33 original comprehension checks and 22 original grammar checks. Cumulative coverage: 50 chapters / 148 distinct comprehension checks reused across reading and listening. Original earlier IDs remain unchanged; excerpts are not claimed to be full Chinese translations or official tests. Action/health/repair scenes are language material, not real-world recommendations. Chapter 43 auxiliary text excludes the sung dialogue; its full recording still needs music/third-party-rights review before publication.
- **New pending review — Lesson 45:** the official Conversation includes the credited song *This Land Is Your Land*, written by Woody Guthrie: https://learningenglish.voanews.com/a/lesson-45-this-land-is-your-land/3710209.html . No new supplementary lessons, question sets or compiled transcript mirror were added for this chapter. Existing local transcript/MP3 copies remain and still enter the default public build, as with Lesson 21. Publisher attribution alone does not clear a third-party composition; verify applicable rights or exclude those works before public release. No blanket statement is made that all remaining full recordings have completed a separate music-rights audit.

- Latest VOA supplements: lessons 31–40, ten Chinese auxiliary lessons, 30 original comprehension checks and 20 original grammar checks. Selected official Conversation excerpts and existing official MP3s retain publisher attribution; Chinese teaching and questions are original, not official quizzes or full Chinese translations. Cumulative supported coverage is 1–20 and 22–40 (39 chapters); 115 comprehension checks are reused across listening/reading, not additional independent exercises. No automatic verified sentence timestamps are published. Lesson 21 remains a separate pending rights review; its existing local assets have not been removed from the default public build.

- Grammar additions: `content/pronouns.py` and `content/prepositions.py` at the same fixed Adam Wang revision, CC BY-SA 4.0. Two additional lessons/12 questions; original earlier lesson/question IDs remain unchanged. Role-based pronoun explanation replaces mechanical position rules; reflexive emphasis need not imply solitude; neither-of ambiguity is excluded; between is not restricted to exactly two items. Content remains separately downloadable under the same license.
- Reading additions: three more SQuAD 1.1 passages (Teacher roles, Oxygen, Steam_engine history), nine original questions and validated source answer spans. Authored multiple-choice options/Chinese explanations remain marked as adaptations, not CET questions. Cumulative open-reading sample: six passages/18 questions.
- VOA additions: lessons 22–30, nine supplementary lessons, 27 original comprehension checks and18 original grammar checks. Cumulative supported chapters: 1–20 and22–30 (29 chapters); 85 comprehension checks reused across listening/reading, not extra independent question counts. Lesson27's medical scene is labelled as language practice, not diagnostic or treatment guidance. No verified automatic audio timestamps are claimed.
- Lesson21 has no new chapter-specific auxiliary unit or bank questions in this batch. Its pre-existing local full recording/transcript are still present and will need removal from a public package or explicit clearance before publication. The app displays this pending-review boundary. Technical build success is not publication authorization.

# 日语真人短句听辨 · 2026-10-18 补充

后续新增批次见下文“N5 TUFS scene-sentence resources — 2026-10-26”；下列七条及许可仍独立保留。

新增7条Tatoeba原始MP3，录音者fal，录音许可为 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。句子来自Tatoeba，原文作者分别为bunbuku、LeviHighway、atitarev、small_snow、kuwasiku，文字许可为 [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/)。两种许可分别适用，不把文字许可套用于音频。音频未剪辑、变声或合成；中文辅助与题目为本站编写。

逐文件原句链接、作者、录音者、许可及哈希见 `public/audio/japanese-listening/credits.json`；页面提供原句与许可链接。使用说明及暂缓项见 `JAPANESE_LISTENING_2026_10_18.md`。贡献者母语程度为自报，尚未经过本站独立人工审听或难度认证。

## CET4 listening structural samples 01–10 — 2026-10-23

VOA Learning English original attributed text and MP3 reports are used under the publisher's [original-content reuse statement](https://learningenglish.voanews.com/p/6861.html), which permits educational and commercial reuse with credit and excludes third-party agency media. Source URLs, original MP3 URLs, author credits, dates and SHA-256 hashes for the 54 newly selected reports are recorded in `src/data/imported/mock-cet4-series-sources.json`; files are hosted in `public/audio/mock-cet4-series/`. The 18 reused Level 1 dialogues are documented in `src/data/imported/mock-cet4-series-conversations.json` and `src/data/publicTutorialCatalog.json`. Original01 sources and records remain unchanged.

The added02–10 question positions consist of153 newly authored report questions and72 reused course comprehension checks; the latter are three-option items, not official four-option CET long-dialogue questions. Chinese explanations are project-authored. No official quiz items, photographs, videos, synthesized replacement audio or third-party agency images were imported in this batch.

Publisher-original attribution is not blanket clearance of embedded third-party works. Candidates involving music, external lecture/film excerpts or substantial third-party textbook narration were moved outside the public package into `local-materials/mock-listening-candidates` for review. All80 final listening-sample files passed publisher-byte-length/hash checks, but this is not a teacher review or an audio-rights sign-off. Before public commercial release, independently review content and each audio track. This batch does not resolve the separate existing VOA lesson21/45 and other site-wide publication-rights issues described above. See `MOCK_LISTENING_TEN_2026_10_23.md` for exact scope and validation limits.

# 六级真人听力02–10结构样板（2026-10-25）

新增63份未剪辑真人MP3及来源文字，来自VOA Learning English的原创Level 2教学对话及跨环境、科技、社区、教育题材的原创报道／采访。明确署名为原VOA记者报道、经Learning English改编者保留其原记者和改编署名。逐文件原页、发布日、署名、原MP3地址、字节长度及SHA-256见 `src/data/imported/cet6-listening-02-04-sources.json`、`cet6-listening-05-07-sources.json`、`cet6-listening-08-10-sources.json`，MP3托管于 `public/audio/mock-cet6-series/`。播放器旁和提交后保留来源。

依据 [VOA原创内容使用说明](https://learningenglish.voanews.com/p/6861.html) 筛选可署名转载的原创文字／MP3，包括商业使用；不导入通讯社素材、照片、视频或官方Quiz。采访中的引用及可能的第三方音轨仍须逐段独立复核；来源署名、字节校验及模型审校不构成全面商用清权。本站225道配题与中文辨析为新编，公开练习不是官方六级题、等难度仿真卷或教师签审教材。08篇章2与09报告3的源文疑点以独立编辑说明标注，未改写来源原句。完整交付与边界见 `CET6_LISTENING_SERIES_2026_10_25.md`；全站其他历史素材的发布限制未由本批解决。

# 六级真人听力01结构样板（2026-10-23）

`public/audio/mock-cet6-01/` 内7份 MP3及对应文字来自 VOA Learning English：Let’s Learn English Level 2 的 Budget Cuts、He Said – She Said；Education Report／Education Tips 的 Tips for Better Writing、More US High Schools Adopt Later Start Times、Tips for Writing: They Say, I Say、Improve Your Writing by Studying Critical Thinking、Managing Large Language Classes。原始URL、发布日、署名、音频URL与SHA-256逐条见 `src/data/imported/mock-cet6-01-sources.json`，播放器旁和提交后也提供来源与署名。

依据 [VOA 内容使用说明](https://learningenglish.voanews.com/p/6861.html) 选择原创文字和MP3，可署名转载，包括商业使用；不导入页面照片、视频、官方测验或通讯社图片。此说明不代表所有被引用作品及第三方音轨均已清权；逐段音轨权利复核仍待完成，不能据本批程序检测宣称已获全面商用授权。本站25题及中文辨析为新编，不属于官方六级题。样板非正式六级篇幅、语速、难度或评分标准；详见 `MOCK_CET6_LISTENING_2026_10_23.md`。

## N5 TUFS scene-sentence resources — 2026-10-26

Twelve unedited Japanese example-sentence MP3s and matching Japanese text are selected from **Tokyo University of Foreign Studies — TUFS Open Language Resources, Basic vocabularies and example sentences**. The publisher lists both the database and MP3 resources under [CC BY 4.0](https://malindo.aa-ken.jp/TUFSOpenLgResources.html); [license text](https://creativecommons.org/licenses/by/4.0/), [official download page](https://www.coelang.tufs.ac.jp/mt/vmod/). Attribution: © Tokyo University of Foreign Studies. Publisher citation: Kawaguchi, Yuji. 2007. “Foundations of Center of Usage-Based Linguistic Informatics (UBLI).” In *Corpus-Based Perspectives in Linguistics*, 3–28. Amsterdam: John Benjamins.

Individual archive URLs, member IDs, original text, credits, byte lengths and SHA-256 are in `src/data/imported/n5-tufs-listening.json` and the publicly downloadable `public/audio/n5-tufs/credits.json`. Audio files are hosted in `public/audio/n5-tufs/`; no edits, concatenation, voice conversion or synthetic substitution were made. Source text retains publisher spacing; Chinese translations, explanations and all questions are authored by YYYYQ. These are twelve independent sentences, not multi-speaker dialogues. Automated recognition, decoding and playback do not establish independent human listening review or JLPT difficulty calibration. Candidate3536 was withheld following a number-recognition discrepancy, not distributed in this public directory.

Four Irodori Starter official full-dialogue pages (lessons6,13,12,10) are linked only; this batch does not copy or embed their recordings or extend their reuse permissions. Earlier local tutorial restrictions remain unchanged. This batch does not resolve unrelated historical materials' publication restrictions. Scope and checks: `N5_APPLICATION_2026_10_26.md`.

