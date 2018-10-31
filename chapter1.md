---
title: 'Chapter one'
description: 'It begins.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Welcome to the jungle, we've got fun and games. 

`@instructions`
Write code to flip 10 fair coins 10 times each.

`@hint`
Try using the function called `rbinom`

`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
#flip 1 fair coin once
rbinom(1,1,0.5)
```

`@solution`
```{r}
rbinom(10,10, 0.5)
```

`@sct`
```{r}

```
