# Blocks

Blocks compose Eve programs

## Syntax



    ```
    match
      ...
    bind or commit
      ...
    ```
    
    ```
    bind or commit
      ...
    ```

## Description

Each block is written in two phases: `match` then `action`. In the `match` phase, we ask Eve for known facts, and we might transform those facts using temporary variables. In the `action` phase we perform some action on the Eve DB to either add or remove facts.

## Examples

A block with match and action phases

```
match
  [name]
bind
  [#div text: name]
```

A black with only a commit phase

```
commit
  [@Stephanie]
```

## See Also

[match phase](match-phase.md) | [action phase](action-phase.md) | [match](match.md) | [bind](bind.md) | [commit](commit.md)
