# Semana 5 de DIW - Relatório de Desempenho.
> **Nota Final:** **`54.93 / 100`**

Olá, **DanielLeoPUC**! 👋

Aqui está o feedback detalhado sobre sua atividade. Use este guia para entender seus acertos e os pontos que podem ser melhorados.

---

## ⭐ Pontos Extras e Boas Práticas
Parabéns! Você completou os seguintes itens bônus, demonstrando um ótimo conhecimento:

#### Tópico: Accessibility
> ✅ **Passou** no teste `check_all_images_have_alt`
> - **Detalhes:** Parabéns! 7 de 7 imagens tem o atributo `alt` preenchido.



#### Tópico: Head detail
> ✅ **Passou** no teste `check_head_details` (Parâmetros: detail_tag: `title`)
> - **Detalhes:** Parabéns! A tag de detalhe `<title>` foi encontrada na seção `<head>`.


> ✅ **Passou** no teste `check_head_details` (Parâmetros: detail_tag: `meta`)
> - **Detalhes:** Parabéns! A tag de detalhe `<meta>` foi encontrada na seção `<head>`.



---

## ✅ Requisitos Essenciais
Encontramos alguns pontos nos requisitos essenciais que precisam de sua atenção:

#### Tópico: Structure
> ❌ **Falhou** no teste `has_tag` (Parâmetros: tag: `div`, required_count: 1)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 tags `<div>`  necessárias.


> - 📚 **Recurso Sugerido:** [Guia completo sobre elementos e tags HTML.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element)


> ❌ **Falhou** no teste `has_tag` (Parâmetros: tag: `form`, required_count: 1)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 tags `<form>`  necessárias.


> - 📚 **Recurso Sugerido:** [Guia completo sobre elementos e tags HTML.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element)


> ❌ **Falhou** no teste `has_tag` (Parâmetros: tag: `button`, required_count: 1)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 tags `<button>`  necessárias.


> - 📚 **Recurso Sugerido:** [Guia completo sobre elementos e tags HTML.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element)



#### Tópico: Link
> ❌ **Falhou** no teste `check_internal_links_to_articles`
> - **Detalhes:** Atenção: ERROR: Test function 'check_internal_links_to_articles' not found.



#### Tópico: Responsivity
> ❌ **Falhou** no teste `uses_relative_units`
> - **Detalhes:** Atenção: Não foram utilizadas medidas relativas como (em, rem, %, vh, vw) no seu CSS.


> - 📚 **Recurso Sugerido:** [Tutorial sobre como usar Media Queries para criar layouts responsivos.](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Media_Queries/Using_media_queries)


> ❌ **Falhou** no teste `check_media_queries`
> - **Detalhes:** Atenção: Não foi encontrado o uso de media queries no seu CSS.


> - 📚 **Recurso Sugerido:** [Tutorial sobre como usar Media Queries para criar layouts responsivos.](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Media_Queries/Using_media_queries)



#### Tópico: Style
> ❌ **Falhou** no teste `has_style` (Parâmetros: style: `font-size`, required_count: 1)
> - **Detalhes:** Atenção: Encontradas0 de 1 `font-size` regras de estilização determinadas.


> - 📚 **Recurso Sugerido:** [Aprenda sobre seletores de CSS e como estilizar elementos.](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/Selectors)


> ❌ **Falhou** no teste `has_style` (Parâmetros: style: `text-align`, required_count: 1)
> - **Detalhes:** Atenção: Encontradas0 de 1 `text-align` regras de estilização determinadas.


> - 📚 **Recurso Sugerido:** [Aprenda sobre seletores de CSS e como estilizar elementos.](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/Selectors)


> ❌ **Falhou** no teste `has_style` (Parâmetros: style: `position`, required_count: 1)
> - **Detalhes:** Atenção: Encontradas0 de 1 `position` regras de estilização determinadas.


> - 📚 **Recurso Sugerido:** [Aprenda sobre seletores de CSS e como estilizar elementos.](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/Selectors)



---

## 🚨 Pontos de Atenção e Más Práticas
Foram detectadas algumas práticas que resultaram em penalidades. Veja os detalhes abaixo para entender como corrigi-las:

#### Tópico: Html
> ❌ **Falhou** no teste `check_id_selector_over_usage` (Parâmetros: max_allowed: 2)
> - **Detalhes:** Cuidado! 7  seletores de ID detecados (limite: 2).


> - 📚 **Recurso Sugerido:** [Aprenda sobre seletores de CSS e como estilizar elementos.](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/Selectors)


> ❌ **Falhou** no teste `check_html_direct_children`
> - **Detalhes:** Cuidado!  A tag <html> deve conter apenas as tags <head> e <body> como filhos diretos.



#### Tópico: Project structure
> ❌ **Falhou** no teste `check_dir_exists` (Parâmetros: dir_path: `imgs`)
> - **Detalhes:** Cuidado! O diretório 'imgs' não existe.


> - 📚 **Recurso Sugerido:** [Entenda como funcionam os caminhos de arquivos em projetos web.](https://developer.mozilla.org/pt-BR/docs/Learn/Common_questions/Web_mechanics/File_paths)



---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Teste e Parâmetros |
|:---|:---|:---|
| Revisar | `structure` | `has_tag`<br><sub>tag: `div`, required_count: 1</sub> |
| Revisar | `structure` | `has_tag`<br><sub>tag: `form`, required_count: 1</sub> |
| Revisar | `structure` | `has_tag`<br><sub>tag: `button`, required_count: 1</sub> |
| Revisar | `link` | `check_internal_links_to_articles`<br><sub></sub> |
| Revisar | `responsivity` | `uses_relative_units`<br><sub></sub> |
| Revisar | `responsivity` | `check_media_queries`<br><sub></sub> |
| Revisar | `style` | `has_style`<br><sub>style: `font-size`, required_count: 1</sub> |
| Revisar | `style` | `has_style`<br><sub>style: `text-align`, required_count: 1</sub> |
| Revisar | `style` | `has_style`<br><sub>style: `position`, required_count: 1</sub> |
| Corrigir (Penalidade) | `html` | `check_id_selector_over_usage`<br><sub>max_allowed: 2</sub> |
| Corrigir (Penalidade) | `html` | `check_html_direct_children`<br><sub></sub> |
| Corrigir (Penalidade) | `project_structure` | `check_dir_exists`<br><sub>dir_path: `imgs`</sub> |

---
> Continue praticando e melhorando seu código. Cada desafio é uma oportunidade de aprender! 🚀