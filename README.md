![NLP_image](https://user-images.githubusercontent.com/105242871/187796413-9539ca0d-70ba-40be-9dca-bb40188afb11.jpeg)

# *️⃣	Resources
# About NLP
## Use Cases
- **Voice of Customer Analytics:** Improve products and services through analysis of customer interactions, such as support emails, social media posts, online comments, telephone transcriptions, i.e., to discover what factors drive the most positive and negative experiences. An example would be to extract key phrases and topics by summarizing blocks of text from open-ended survey responses in order to extract the most important and central ideas that can lead to actionable insights.

- **Semantic Search:** Provide a better search experience by enabling your search engine to index key phrases, entities, and sentiment. This enables you to focus the search on the intent and the context of the articles instead of basic keywords.

- **Knowledge Management & Discovery:** Organize and categorize your documents by topic for easier discovery. You might want to personalize content recommendations for readers by recommending other articles related to the same topic. Or you might want to ensure the security of documents by closely monitoring those documents containing sensitive materials (Topic Modeling).

## Methods
#### Text Classification
- Assign tags or categories to text according to its content.

- Applications: sentiment analysis, topic labeling, spam detection, and intent detection.

- Similar to topic modeling, but is supervised learning, so the set of possible classes are known/defined in advance.

#### Topic Modeling
- Discover the abstract “topics” that occur in a collection of documents.

- Latent Dirichlet Allocation (LDA) is a commonly used algorithm.

- Similar to text classification but is unsupervised, like clustering, so the set of possible topics are unknown prior. The topics are defined as part of generating the topic models.

***

# Regular Expressions
A **regular expression** is a sort of meta-language that can be used to describe patterns in text.

Regexes are most commonly used in one of two ways:

- To find/extract text that matches a pattern.
- To replace/substitute text that matches a pattern.

## Metacharacters and Character Classes
metacharacter |	matches
| :---: | :---: |
`.`	|anything
`\w` |	any letter or number
`\W` |	anything that's not a letter or number
`\d`	| any digit
`\D`	| anything that's not a digit
`\s`	| any whitespace character

## Repeating
metacharacter	| matches
| :---: | :---: |
`*`  |	zero or more
`+`	| one or more
`{n}` | exactly n repititions
`{n,}`	| n or more repititions
`{n,m}` | between n and m repititions
`?`	| an optional character

## Anchors
metacharacter	| matches
| :---: | :---: |
`^`	| The start of the string/line
`$`	 | The end of the string/line
`\b`	| A word boundary

## Other Common Functions
- `match`: Matches from the start of the string.
- `search`: Find the first instance of the regular expression.
- `sub`: Make substitutions with a regular expression.
- `compile`: Prepare a regular expression for use ahead of time.

## Capture Groups
We can define groups in our regular expressions called **capture groups**. This allows us to reference the groups later on in the regular expression, or apply repitition to the group as a whole.

Note that when we include capture groups in our regular expressions, `findall` will return only the matched groups, not the entire text that was matched.

## Regex Flags
- `re.MULTILINE`: The ^ and $ anchors will apply line by line, instead of applying to start and end of the string.

- `re.IGNORECASE`: Ignore character casing when matching.

- `re.VERBOSE`: Ignore any whitespace in the regular expression. This can be useful to make more readable regular expressions, especially when combined with non-capturing comment groups.




# *️⃣ Exercises
