{% macro project_card(title, image_url, date, description, path_url, path_text, related_url, related_text) %}
<br/>
![{{ title }}]({{ image_url }}){ width="413" }

## — {{ title }}
- **Date:** `{{ date }}`
- **Description:** {{ description }}
- **Path:** [{{ path_text }}]({{ path_url }})
- **Related Files:** [{{ related_text }}]({{ related_url }})

---
{% endmacro %}

--8<-- "includes/project_card.md"

# Next Level Week Projects

=== "NLW #1"

{{ project_card(
    "Ecoleta",
    "https://raw.githubusercontent.com/mateusloubach/ecoleta-app/refs/heads/main/.github/logo.png",
    "01 — 07 de Junho de 2020",
    "O Ecoleta é uma aplicação Web e Mobile para ajudar pessoas a encontrarem pontos de coleta para reciclagem...",
    "https://github.com/mateusloubach/ecoleta-app",
    "github.com/mateusloubach/ecoleta-app",
    "https://github.com/rocketseat-education/nlw-01-omnistack",
    "github.com/rocketseat-education/nlw-01-omnistack"
) }}

=== "NLW #2"

{{ project_card(
    "Proffy",
    "https://example.com/proffy-logo.png",
    "03 — 09 de Agosto de 2020",
    "Proffy é uma plataforma de ensino que conecta professores e alunos...",
    "https://github.com/mateusloubach/proffy",
    "github.com/mateusloubach/proffy",
    "https://github.com/rocketseat-education/nlw-02-omnistack",
    "github.com/rocketseat-education/nlw-02-omnistack"
) }}
