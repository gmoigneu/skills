# Agent skills

[![skills.sh](https://skills.sh/b/gmoigneu/skills)](https://skills.sh/gmoigneu/skills)

Skills I use to make AI agents more useful in real work. Each skill is self-contained and can be installed independently.

## Available skills

### [Pressure-test decisions](skills/pressure-test-decisions/)

Challenge assumptions, widen the options, test uncertainty, and turn a difficult decision into a defensible choice or concrete next action.

```sh
npx skills add gmoigneu/skills --skill pressure-test-decisions
```

## Browse the repository

List every available skill without installing anything.

```sh
npx skills add gmoigneu/skills --list
```

Install all skills from this repository.

```sh
npx skills add gmoigneu/skills --all
```

## Repository layout

Each public skill lives under `skills/<skill-name>/` and keeps its instructions and supporting files together.

```text
skills/
  pressure-test-decisions/
    SKILL.md
    agents/
      openai.yaml
    references/
      books.md
      methods.md
```

## Adding a skill

1. Create `skills/<skill-name>/SKILL.md`.
2. Add valid `name` and `description` fields to its YAML frontmatter.
3. Keep references, scripts, and assets inside the same skill directory.
4. Run `npx skills add . --list` before committing.

## License

Apache-2.0.
