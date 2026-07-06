# Contributing

Thanks for helping improve this list.

## What to Add

Good additions include:

- papers on SOD, COD, RGB-D SOD, RGB-D COD, VSOD, VCOD, COS, and joint SOD-COD learning;
- SAM, VLM, MLLM, or foundation-model adaptation for foreground segmentation;
- datasets, benchmarks, evaluation code, and survey papers;
- reading notes that explain why a paper is worth tracking.

## Entry Rules

Please keep entries easy to check:

- include a stable paper link, such as arXiv, CVF Open Access, IEEE, ACM, Springer, OpenReview, or the project page;
- include code only when the link is public and official or clearly maintained by the authors;
- use tags from [`docs/taxonomy.md`](docs/taxonomy.md) when possible;
- keep the tag column short and informative;
- avoid adding papers that are unrelated to object-level foreground segmentation.

## Pull Request Checklist

- [ ] The paper is placed in the most relevant section.
- [ ] The entry uses the standard table format.
- [ ] Links are public and work.
- [ ] The tags are consistent with the taxonomy.
- [ ] New datasets are also added to `data/datasets.yaml` when relevant.

## Suggested Paper Entry

```markdown
| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Paper Title | `SAM` `Open-Vocab` | [Paper](url) / [Code](url) |
```

## Suggested YAML Entry

```yaml
- title: "Paper Title"
  year: 2026
  venue: "CVPR"
  tasks: ["SOD-COD"]
  modalities: ["RGB-D", "Prompt"]
  settings: ["Full"]
  methods: ["SAM", "Fusion"]
  paper: "https://example.com/paper"
  code: "https://github.com/example/repo"
  note: "One short reason this paper is useful."
```
