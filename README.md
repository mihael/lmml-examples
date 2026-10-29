# LMML examples

**Language Model Markup Language.** A tongue-twisting name for a simple experiment: what if a website were just Markdown and media?

Born from a conversation between [Miha Plohl](https://manitu.si/) and AI, then turned into a comic that contains the document that contains the comic.

LMML is a playful proposed name, not a formal standard, parser, or new Markdown dialect. These examples use ordinary Markdown, relative links, images, and optional YAML front matter. No special software is required.

## Examples

- [Minimal page](examples/minimal/index.md): a page with text, an image, and a link.
- [Consultant profile](examples/consultant/index.md): services and contact information an assistant can read.
- [Recursive comic](examples/recursive-comic/index.lmml.md): the original article, the comic, its plain-text transcript, and a link back to itself.
- [llms.txt](llms.txt): a curated map of this repository for agents.

[Read the live article and example on manitu.si](https://manitu.si/articles/human-readable-websites-are-dead/).

## The experiment

1. Put the information in Markdown.
2. Link media with descriptive alternative text.
3. Include a transcript when an image contains important dialogue.
4. Connect pages with normal links.
5. Optionally provide an `llms.txt` overview.

Images still require vision capabilities to interpret; a text-only reader can use the alternative text and transcript. A public file is accessible to agents, but that does not guarantee discovery, indexing, or citation.

`llms.txt` is a separate [community proposal](https://llmstxt.org/), not part of an invented LMML specification. GitHub renders these documents for people and serves their raw source for machines.

## Read without GitHub's interface

Open a document on GitHub and select **Raw**, or fetch it through `raw.githubusercontent.com/mihael/lmml-examples/main/` followed by its repository path.

For example:

```sh
curl -L https://raw.githubusercontent.com/mihael/lmml-examples/main/examples/recursive-comic/index.lmml.md
```

## Contributing

Small, understandable examples welcome. Use relative links, include text alternatives for important media content, and label fictional data clearly. Never include credentials or private information.

## Credits

Article: Miha Plohl. Comic: AI-generated with OpenAI's image generator. The recursive example preserves the author's original wording.
