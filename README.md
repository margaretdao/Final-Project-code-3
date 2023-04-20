# Final-Project-code-3
Regular expression


library(stringr)


Verb_words <- c('Running', 'Punching', 'Cooking', 'Swimming', 'Dancing')
Verb_words_regular_expr <- str_match(Verb_words, '[aeiouAEIOU]{2,}')
Verb_words_regular_expr
