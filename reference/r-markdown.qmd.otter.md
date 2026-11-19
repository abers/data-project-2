
























































































































# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6











Single asterisks creates *italicised* and double asterisks
creates **bold** text.

- Dashes `-` create lists.
  - Add spaces at start of line before the dash.
  - To create indented lists.

1. Adding numbers at the start.
2. Will create a numbered list.


















When knitted the below text
# will not appear as a header
because there is no line spacing

When knitted the below text

# will appear as a header

because there is line spacing















# Data Cleaning

## Coercing the age variable

```{{r coerce-age}}
# age is read in as text, so need to transform the variable to numeric
police <- police |> mutate(age = as.numeric(age))
```
