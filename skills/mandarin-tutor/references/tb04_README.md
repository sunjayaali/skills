# 當代中文課程　第四冊

# A Course in Contemporary Chinese — Textbook 4

**Mandarin Training Center, National Taiwan Normal University**
國立臺灣師範大學國語教學中心

**Chief Editor｜主編：** Shou-Hsin Teng 鄧守信

---

## 目錄 Table of Contents

| Lesson | 課 | Title | English |
| --- | --- | --- | --- |
| 1 | 第一課 | 十七歲還是二十五歲？ | 17 or 25-Years Old? |
| 2 | 第二課 | 眼睛、耳朵的饗宴 | A Feast for the Eyes and Ears |
| 3 | 第三課 | 科技生活 Technology & Daily Life | *(title pending)* |
| 4 | 第四課 | 床該擺哪裡？ | Where Should the Bed Go? |
| 5 | 第五課 | 有夢最美 | Pursuing Your Dreams |
| 6 | 第六課 | 天搖地動 | Shaking Heavens and Trembling Earth |
| 7 | 第七課 | 大學生的事 | College Student Matters |
| 8 | 第八課 | 他們的選擇 | Their Choice |
| 9 | 第九課 | 再談台灣故事 | More on the Story of Taiwan |
| 10 | 第十課 | 應徵 | Applying for a Job |
| 11 | 第十一課 | 文化、種族的大熔爐 | The Big Cultural and Ethnic Melting Pot |
| 12 | 第十二課 | 期待美好的未來 | Looking Forward to a Beautiful Future |

### Topics by lesson

| Lesson | Topic |
| --- | --- |
| 1 | 網路 Internet |
| 2 | 藝術活動 Arts |
| 3 | 科技生活 Technology & Daily Life |
| 4 | 風水 Feng Shui |
| 5 | 經濟情況 Economic Conditions |
| 6 | 地震 Earthquake |
| 7 | 大學生活 College Life |
| 8 | 社會現象 Social Phenomena |
| 9 | 歷史 History |
| 10 | 就業 Employment |
| 11 | 社會結構的改變 Social Structure Change |
| 12 | 政治 Politics |

---

<!--
Notes for maintainers / study agents:

- Lesson files live alongside this README as `tb04_lNN.md` (NN = 01…12).
  This dataset covers all twelve lessons of Textbook 4.
- Every lesson follows the same top-level section skeleton:
  學習目標 Learning Objectives → 對話 Dialogue → 生詞（一）Vocabulary I →
  短文 Reading → 生詞（二）Vocabulary II → 文法 Grammar →
  Grammar Examples in English → 課室活動 Classroom Activities →
  中華文化點滴 Bits of Chinese Culture → 自我評量 Self-Assessment Checklist.
  A section appears only where the textbook itself has it. Book 4 names the
  reading 短文 (short passage) where Books 2–3 use 閱讀.
- Deviation from that skeleton: `語法例句 Grammar Examples in English` is a
  top-level section only in Lessons 2–6 and 12; the other lessons keep their
  English examples inside 文法 Grammar. No lesson adds a top-level 練習 Exercise
  section, unlike Textbook 3's Lesson 12; exercises nest as `#### 練習 Exercise`
  under their grammar point. Lesson 4's 課室活動 (我所知道的風水 / 到底是不是風水的問題？)
  sat unheaded in the middle of the OCR dump rather than in its own section.
- Both the 對話 and 短文 sections carry a `Text in Simplified Characters` and an
  `English` sub-block, with these exceptions: Lesson 3's dialogue carries
  neither (its 短文 carries both); Lesson 4's 對話 and 短文 each carry only
  the Simplified sub-block (`簡體字版` / `課文簡體字版`) and no `English`
  translation.
- Pinyin: Book 4 prints no romanization in the source. All pinyin in these files
  is editorial, reconstructed from the hànzī; it is not printed in the textbook.
  Vocabulary readings and 詞類 part-of-speech labels follow the Drive vocabulary
  deck (`B4-LNN.pdf`), which is the authority on tone marks — settle every
  vocabulary cell against it before teaching. Every lesson states this in a
  `Front-matter note` under the title.
- Source: an OCR scan of the printed textbook. Obvious OCR errors were corrected
  where the intended text was unambiguous. Passages that could not be confidently
  reconstructed are marked `[OCR uncertain]` inline rather than guessed — currently
  two such marks, both in Lesson 6, both illegible zhuyin columns.
- Traditional characters (繁體中文) are the primary form, as printed.

Known gaps and OCR damage in this dataset, listed so a study agent does not
mistake them for intentional structure:

- Lesson 3's title was never transcribed from the scan, so its H1 reads
  `# 第三課 [title not transcribed in source]`. That placeholder is deliberate —
  do not invent a title. Its `**Topic：**` line has been used as a provisional
  stand-in in the table above. Lesson 3 lacks the romanized and English title
  lines the other lessons carry.
- Section-name drift, all OCR artifacts rather than real variation: Lesson 3
  writes 課堂活動 Classroom Activities and Lesson 12 writes 課室活動 Activities,
  against 課室活動 Classroom Activities elsewhere; Lesson 3 titles its last
  section 自我檢測 Self-Assessment, without the `Checklist` suffix; Lesson 12
  writes 自我評量 Self-Assessment, also without `Checklist`. Lessons 3 and 4
  both had 中華文化 corrupted to 文彳匕 (`文彳匕 Bits of Chinese Culture`);
  Lesson 4's copy is now corrected, Lesson 3's is not. Lesson 4 also prints
  自我檢測 rather than the 自我評量 used elsewhere — that one is left as
  printed, since it is a real variant and not clearly damage.
- Lesson 11's dialogue heading is `## 對話 Dialogue C11-01`, with a stray `C`,
  against `對話 Dialogue NN-01` in every other lesson.
- Lesson 6 preserves the textbook's fixed-width two-column layout in places,
  using long underscore rules and space-padded columns. Leave that spacing
  alone — reflowing it destroys the column alignment.
- Lesson 4 was reworked from a raw two-column OCR dump into the same markdown
  shape as the other lessons: running heads, page furniture, and interleaved
  columns are gone, vocabulary is now `# | 生詞 | Pinyin | 詞類 | English`
  tables, the dialogue and reading are speaker-labelled bold lines, and the
  zhuyin column that OCR had shredded into stray CJK glyphs (五, 刁, 厶, ...)
  is dropped — Book 4 prints no romanization, and the editorial pinyin column
  is the readable one. Its 文化 figure captions are kept as blockquotes under
  a `**Figure:**` label, since the images themselves are not in these files.
- `SKILL.md` covers Textbooks 1–4 and carries a Book 4 content-map and
  lesson-anatomy entry.
-->
