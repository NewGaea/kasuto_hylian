---
tag: documentation standards hylian-linguistic-society
---
# HLS Documentation Standards
---
The Hylian Linguistic Society seeks to make the documentation of this language as accessible as possible. To this end, we are developing standards to make it easy for both the layperson and linguist to access information suitable to their interest in the Hylian Languages we maintain.

## 1. Be Consistent

It is our goal to be as consistent in the look and feel of our work as possible. This ranges from the choices we make when formatting our Markdown to the places we choose to use HTML in place of Markdown. It includes everything from list formatting to file naming conventions.

### 1.a | Markdown Consistency
When using Markdown as the primary formatting method for our files, we prefer to establish a concisistent set of rules for our contributors.

#### 1.a.1 | Use of Asterisks and Underscores
We prefer to distinguish between **bold/strong** and _italic/emphasis_ formatting. To this end, it is our recommendation that contributors to this project use \*\* marks to indicate **\*\*bold/strong\*\*** formatting, and \_ marks to indicate \__italic/emphasis_\_ formatting. Where both formats are used on exactly the same segment of text, we prefer to enclose _emphasis_ within **strong,** creating **\*\*\__strong emphasis_\_\*\*** in a visually distinct manner.

#### 1.a.2 | Link Formatting
We recommend the use of Traditional Markdown Links, using \[label\]\(address\) syntax. While \[\[Wikilink\]\] is acceptable, it is preferred in the long term to convert \[\[Wikilink\]\] syntax to traditional markdown syntax over time. The reason for this is that while **Obsidian Markdown** supports wikilinks, not all Markdown parsers do.
We recognize the hypocrisy of using \[\[Wikilink\]\] syntax as we establish this vault and documentation, but we are committed to removing wikilinks at a later date.

### 1.b | Orthographic Consistency
As we are documenting a language, we seek to maintain consistent spellings throughout our work. However, there are several ways to compose the Hylian Language at this point in time, and we encourage all of our contributors to familiarize themselves with [at least two](standards/orthography/comparison).

#### 1.b.1 | [Kasutan Font-Mapped Hylian](standards/orthography/kasuto-font)
This is the name we use for the original font-mapped orthography used by **[Kasuto of Kataan](contributors/kasuto)** when he began publishing the language with a font he produced himself. It uses symbols like \<, @, and \[ to encode letters or digraphs, which can make it difficult to read if you are not using the Kasutan Fonts, or a compatibly mapped font. However, we are preserving this mapping for the [archive of Kasuto's site](archival/kasuto_hli/00-toc) which we maintain for its historical value.

#### 1.b.2 | [Kasutan Romanization](standards/orthography/kasuto-roman)
This is the official romanized form of Hylian produced by Kasuto, which we maintain similarly to **Kasutan Font-Mapped Hylian,** with the primary purpose being to preserve Kasuto's old work, but also the archived work from the Vinculum Forums, which saw a number of fans contribute to the language.

#### 1.b.3 | [Springerian Romanization](standards/orthography/springer-roman)
This is the romanization used by **[Austin Springer](contributors/austin_springer)**. It is a case-sensitive romanization which incorporates the six letters which **Kasuto** announced on the Vinculum Forums. Is is, in a sense, an adaptation of **Kasutan Font-Mapped Hylian,** though with a commitment to only using alphabetic symbols.

#### 1.b.4 | [HLS Plaintext Romanization](standards/orthography/jerin-roman)
Upon taking the reins of the project, **[Jerin of Calatia](contributors/jerin_of_calatia)** set to establish a new standard romanization. In large part, their goal was to make an orthography that would be elegant and readable even for individuals with little or no prior knowledge of the language. The orthography that results is the official romanization scheme of the HLS as of July 2023, keeping the language largely typeable on most US keyboards without trouble.

#### 1.b.5 | [HLS IPA Romanization](standards/orthography/jerin-ipa)
For linguists, or experienced conlangers, **Jerin of Calatia** has also mapped all of the letters used in Classical Hylian to IPA symbols. This romanization is found in the advanced grammar documents as well as the full dictionary.

### 1.c | **Link Usage**
Links should be used generously in order to track information on the language, and to connect information across the project. We consider it ideal to ensure that every note has at least one incoming link and one outgoing link, and that no two notes exist which, between them, only link to each other.

#### 1.c.1 | Archival Links
Links going into the **archival** directory are historical references. They should generally be used to cite the historical record, and should generally not be used to deny modern updates proposed by the HLS.

#### 1.c.2 | User Links
Most notes outside of the **archival** directory should link back to at least one **contributor** as an author or source.

#### 1.c.3 | Navigation Links
Most notes outside of the **archival** directory should contain some link to navigate to at least one connected page.