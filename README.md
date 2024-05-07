# InfiniteContextGPT

This program allows you to pseudo extend the token limit of chatGPT to effectively unlimited. It does this by encoding sentences into a 384 dimension embedding space and them determines the sentences the most similar to the question and feeds those sentences to ChatGPT with the question.

# To Run

run each cell in order. Then in the final cell you will be asked for your open api key. Then If your reference text is a webpage enter the link. If your reference text is a pdf enter "PDF" then enter the file name. The pdf needs to be in the same folder. Then once you have got your chosen reference text it will repeatedly ask you for a question and provide the answer. If you want to change the reference text enter "QUIT"
