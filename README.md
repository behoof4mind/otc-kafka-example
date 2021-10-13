# OTC CCE Apache Kafka examples

### How to change and export
- Make some changes in .md files
- Export to the needed formats by [pandoc](https://pandoc.org/):
  - Markdown to Docx:
      ```shell
      pandoc -f markdown -s OTC-Kafka-example.md -o OTC-Kafka-example.docx
      ```
  - Markdown to PDF:
      ```shell
      pandoc --pdf-engine=xelatex OTC-Kafka-example.md -o OTC-Kafka-example.pdf --toc
      ```
  
### Contribution
If you found any mistakes or have improvements/ideas, please let us know by opening Issue or Merge request.