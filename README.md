# Turtle observations data model

Documentation for the modeling of data captured when observing turtles and turtle nests.

## Why?

In Panamá, there are a number of organisations involved in the tracking and monitoring of wild turtles. Currently, there is no standard as to what data is captured, and data is not easily shareable between organisations.

By working together to create a unified data model, organisations can collaborate and share data more effectively, deepening insights into the lives of turtles, and improving the effectiveness of conservation and education of these beautiful creatures.

This project serves as a living document and proposal for a common standard by which organisations can capture data about turtles.

## Contributing

This is an open source project - we welcome and encourage discussion and feedback so that we can improve our understanding of what data is important to capture, how to capture it, and how the data matters to different people and organisations. 

Please see our [code of conduct](./CONTRIBUTING.md) if you would like to get involved.

### How to contribute

If you see room for improvement in this project, feel free to open an issue and start a discussion. You'll need a GitHub acccount before you can take part in discussions on issues.

For the more adventurous, you may also contribute to the project by making changes directly to the files. Many of the files in this project are written using _markdown_ - please see [Markdown Guide][external-markdown] for tips and tricks to write markdown. In order for you to make changes to files, you'll need to do the following:

- ensure you have forked this repository
- create a new branch where you will make changes to files
- make changes to the files
- submit a pull request to this repository

freeCodeCamp has a great guide on [how to fork a repository][external-freecodecamp-forking].

Once we have your pull request, maintainers and anyone interested can discuss your changes, after which your changes may or may not be approved and merged into this repository. It's usually a good idea to first open an issue before putting effort into making changes to files.

### Diagrams

The diagrams in this project are written using the [Mermaid Js][external-mermaidjs] syntax. To ensure that we maintain a history of changes to diagrams, please ensure that any diagrams you submit are submitted as follows. Please see [GitHub's guide][external-github-diagrams] on how to create diagrams in markdown files.

When adding erDiagrams:

- all fields belonging to the entity should be rendered in the diagram
- only immediately related entities should be rendered in the diagram
- related entities should only show fields important to the relation

## TODO

- [x] add notes on how to write markdown
- [x] add notes on how write docs
- [x] add notes on how to write plant UML / MermaidJs
- [ ] add docs for data model using plant UML / MermaidJs
  - [ ] add ERD diagrams and adjacent relations for all models
  - [ ] add caveats for different fields, depending on their context (i.e. spreadsheet vs Airtable vs RDB)
- [x] add contributing file

<!-- LINKS -->
[external-markdown]: https://www.markdownguide.org/basic-syntax/ "Markdown syntax guide"
[external-freecodecamp-forking]: https://www.freecodecamp.org/news/how-to-fork-a-github-repository/ "freeCodeCamp - How to fork a GitHub repo"
[external-github-diagrams]: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams "GitHub - creating diagrams"
[external-mermaidjs]: https://mermaid-js.github.io/mermaid/#/ "Mermaid Js"
[external-plantuml-proxy]: https://stackoverflow.com/a/32771815 "Stackoverflow - PlantUML in GitLab / GitHub"
