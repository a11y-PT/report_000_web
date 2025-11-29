---
website: "Nome do sítio Web"          # Entre as aspas escreve o nome do website
date: "31/12/1999"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
url: "https://dominio_sitio_web.pt"   # Entre as aspas escreve o domínio do website
owner: "Nome do proprietário"         # Entre as aspas escrever o nome do owner do website
seal: "Ouro"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.url }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
  
## Relatório de Auditoria

Consulte aqui a última atualização: [Relatório do {{ page.website }}](report_001.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="31121999_report_001.html">(31/12/1999). Relatório do {{ page.website }}</a></li>
  </ul>
</details>
