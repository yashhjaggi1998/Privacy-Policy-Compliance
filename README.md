# Privacy-Policy-Compliance

This project is designed to help naive social media users with the complicated privacy policies of social media applications. Due to the complexity of the language and ignorance from users, they fail to read and understand if any privacy policy is harmful for them.
For instance, users agree to the terms of whatsapp without reading the policies as they are very lengthy and tidious to read. It can be a possibility that some apps might sell user data or use that data for unwanted reasons.

As a solution to this problem, we have developed a model in Natural Language Processing to classify text into different policies involved in G.D.P.R. laws, shorten and simplify the resulting text. Additionally, we rank the policies as red, orange or green flags depending on how harmful the policies are.

By classify, we mean segregate the sentneces into various buckets such as 3rd party data sharing, data theft, etc. to name a few.
To classify we have used supervised classification algorithms and for the grading of harmful policies we have trained and developed a custom RNN model.
