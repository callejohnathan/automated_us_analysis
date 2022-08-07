<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 Automated User Stories Analysis: a Named Entitiy Recognition (NER) approach

NER model for identifying Actors, Functions, and Concepts from user stories. Such a model is based on the spaCy language model and trained on the PURE dataset.

You may find the training and validation datasets in the "corpus" folder, including json files and spaCy-based format files.

## 📋 project.yml

The [`project.yml`](project.yml) defines the data assets required by the
project, as well as the available commands and workflows. For details, see the
[spaCy projects documentation](https://spacy.io/usage/projects).

### ⏯ Commands

The following commands are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run).
Commands are only re-run if their inputs have changed.

| Command | Description |
| --- | --- |
| `train` | Train the full pipeline |
| `evaluate` | Evaluate on the test data and save the metrics |
| `clean` | Remove intermediate files |

### ⏭ Workflows

The following workflows are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run)
and will run the specified commands in order. Commands are only re-run if their
inputs have changed.

| Workflow | Steps |
| --- | --- |
| `all` | `train` &rarr; `evaluate` |



<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->
