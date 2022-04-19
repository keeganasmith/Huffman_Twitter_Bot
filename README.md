# Huffman_Twitter_Bot
TLDR:Bot that uses the huffman coding algorithm to compress tweets with the keyword "compress" and can decode those messages with the keyword " decode ". Twitter bot username is @bot90861498. Bot must be mentioned in the tweet. I also can't guarantee the bot will be up 24/7, it is running on a server through heroku and I'm kinda cheap :(

How it works/how it uses the twitter api: Through tweepy/python and some authentication keys it uses the twitter API. From there, it uses the twitter API to sort through statuses (tweets) that it was mentioned in. To prevent the bot from replying to statuses (tweets) that it has already replied to, it adds the id of every mention to a list and before every tweet it will check to make sure the id of the mention is not contained in this list. When the bot replies to a mention, it adds the mention id to the list. My bot also uses the twitter api to create statuses (tweet)

Huffman algorithm: This symbol code compression algorithm traditionally uses a priority queue and a binary tree to sort and encode messages based on the frequencies of characters. In my implementation I used a list instead of a pqueue, but it functions just as well. 





