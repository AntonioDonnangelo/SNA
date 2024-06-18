# SNA
Final project Social Network Analysis (Master Big Data and AI)

## The Edinburgh Associative Thesaurus:
The Edinburgh Associative Thesaurus (EAT) is a set of word association norms showing the counts of word association as collected from subjects. This is not a developed semantic network such as WordNet (3), but empirical association data.

The traditional way to collect word association norms is to show or say a word to several people and ask them to say the word which first comes to their minds upon receiving the stimulus. The link established between the stimulus and the response is not semantically labelled (e.g. as synonym, antonym or by a case relation) and can only be regarded as an association.

The Edinburgh association norms were collected by growing the network from a nucleus set of words. Responses were collected to words in this nucleus set, then these responses were used to obtain further responses, and so on. In fact the cycle was repeated about three times since by then the number of different responses was so large that they could not be re-used as stimuli. Data collection stopped when 8400 stimulus words had been used. Each stimulus word was presented to 100 different subjects, each of whom received 100 words. This gave rise to a total of 55732 nodes in the Thesaurus network.

The subjects were mostly undergraduates from a wide variety of British universities. The age range of the subjects was from 17 to 22 with a mode of 19. The sex distribution was 64 per cent male and 36 per cent female. The data was collected between June 1968 and May 1971.

The database consists of two files. The SR (stimulus-response) file, and the RS (response-stimulus) file. Where words have been truncated to 19 characters to save space the per cent character (%) has been placed as the 20th.

The EAT here is that included in the MRC Psycholinguistic Database (4), for use with the other measures available there.

## Reuters terror news network:
Reuters terror news network Days.net in Pajek's format obtained from the CRA networks produced by Steve Corman and Kevin Dooley at Arizona State University.
Please acknowledge this when publishing results based on these data.

The Reuters terror news network is based on all stories released during 66 consecutive days by the news agency Reuters concerning the September 11 attack on the U.S., beginning at 9:00 AM EST 9/11/01. The vertices of a network are words (terms); there is an edge between two words iff they appear in the same text unit (sentence). The weight of an edge is its frequency. The network has n = 13332 vertices (different words in the news) and m = 243447 edges, 50859 with value larger than 1. There are no loops in the network.

The network DaysAll.net contains the main connected component of the network obtained by transforming the Reuters terror news network into a combined network for all 66 days (union of all time points). It has 13308 vertices.

The Reuters terror news network was used as a case network for the Viszards visualization session on the Sunbelt XXII International Sunbelt Social Network Conference, New Orleans, USA, 13-17. February 2002.
