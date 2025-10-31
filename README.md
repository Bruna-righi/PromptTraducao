# PromptTraducao

## Identificação de problemas
Problemas encontrados no texto:
- Artigos posicionados atrás do substantivo;
- Vírgulas em posições incorretas;
- Uso incorreto de 'who' e 'that';
- Números escritos de maneira inconsistente;
- Preposições usadas de maneira incorreta;
- Verbos sem concordância com o sujeito da frase, ou que estão no tempo incorreto;
- Uso de substantivos no lugar de verbos e vice-versa;
- Informalidade em certas sentenças;
- Uso de aspas para ênfase;
- Repetição de palavras numa mesma frase;

## Regras Geradas
1. Sem vírgulas antes de ‘e’ quando for conjunção;
2. Usar ‘that’ ao se referir a um objeto ou conceito;
3. Usar adjetivos somente antes de substantivos;
4. Consistência ao usar números: somente por escrito ou somente numerais;
5. Escolher sinonimos mais formais;
6. Corrigir erros com relação à gramática das palavras, como letras a mais, digitações incorretas, etc;
7. Usar letras maiúsculas somente em nomes;
8. Conjugar verbos corretamente, se atentando ao tempo verbal da frase, e levando em conta o contexto;
9. Não utilizar substantivos quando o sujeito da frase está descrevendo uma ação - substitua pelo verbo correto;
10. Contextualizações (como frases adverbiais de tempo e espaço) deslocadas na frase devem ser separadas do resto por vírgula;
11. Quando relatando uma sequencia de acontecimentos, os separe por vírgulas
12. Não use aspas se a frase não for uma citação direta;
13. Utilize a conjunção correta de acordo com o contexto. Julgue baseado na palavra anterior e na seguinte;
14. Não utilizar expressões informais;


## Prompt Final

```
When correcting the text delimited by { and }, apply the following:
Academic Tone
 Maintain a formal, objective, and concise academic tone.
 Avoid colloquial language, idioms, and emotional or subjective expressions.


Clarity and Precision
 Ensure sentences are clear, logical, and unambiguous.
 Replace vague or informal terms with precise academic equivalents.
 Use active voice where it improves clarity; keep passive voice where standard.


Grammar and Syntax
 Correct all grammatical errors, including tense, agreement, and article usage.
Correct typos and spelling mistakes.
Avoid repeating the same word twice in a sentence.
 Use past tense for case descriptions and present tense for general facts.
 Keep parallel structure in lists and consistent terminology throughout.


Punctuation and Structure
 Use commas, colons, and semicolons correctly.
 Avoid run-on sentences, fragments, and unnecessary punctuation.


Capitalization and Formatting
 Capitalize only proper nouns, section titles, and standard abbreviations (e.g., MRI, NICU).
 Keep generic terms lowercase. Maintain section titles in bold.


Spelling and Units
 Follow U.S. English spelling.
 Use standard SI units and consistent formatting: “33°C,” “3,055 g,” “46.5 cm.”
 Space between number and unit, except for °C.


Articles and Determiners
 Use “the” for specific nouns, “a/an” for general ones.
 Omit unnecessary articles before plural or uncountable nouns.


Prepositions and Phrasal Verbs
 Ensure correct combinations:

“associated with,” not “associated to.”
“resulted from,” not “resulted by.”
“followed at the clinic,” not “followed in.”

 Prefer formal verbs over informal phrasal ones.

Numbers and Data
 Spell out one–nine (unless with units or data).
 Keep measurement and numerical style consistent.


Flow and Cohesion
 Maintain consistent terminology and smooth transitions (“thus,” “subsequently,” “therefore”).
 Avoid redundancy and ensure logical section flow.


Output
 Return the corrected text, preserving structure, section headings, and formatting, and after the text, explain why each correction was made.
```
