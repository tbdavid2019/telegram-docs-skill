# Type: RichBlockMathematicalExpression

**Category**: Rich messages

**Description**: A block with a mathematical expression in LaTeX format, corresponding to the custom HTML tag <tg-math-block>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockmathematicalexpression)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "mathematical_expression" |
| expression | String | Yes | The mathematical expression in LaTeX format |
