# Character Interaction Networks for the Harry Potter Series
In the realm of J.K. Rowling's magical world, character interactions form a web of relationships that enrich the storytelling experience. These networks have been meticulously constructed by establishing connections between two characters whenever their names or nicknames are mentioned within a proximity of 14 words in any of the books from the Harry Potter series. The weight of each connection represents the frequency of their interactions.

This data offers an exciting opportunity to delve into the intricacies of the Harry Potter universe using network science techniques. Here are some ways in which you can leverage this dataset:

1. Community Detection: Apply community detection algorithms to uncover coherent plotlines within the series. Characters that interact frequently might belong to the same community, revealing the dynamics of various groups and alliances in the wizarding world.
2. Centrality Measures: Utilize centrality measures, such as degree centrality or betweenness centrality, to identify the pivotal characters in the saga. Who are the central figures whose actions or relationships significantly impact the story's progression?
3. Character Analysis: Explore the data to gain insights into character development. Has a character's network evolved over the course of the series? Who are the characters with the most diverse network of connections?
4. Sentiment Analysis: Combine the interaction data with sentiment analysis to determine the emotional tone of character interactions. Are there patterns of positivity or negativity in these interactions?
5. Temporal Analysis: Study the network's evolution over time, tracking how relationships between characters change as the series progresses. Are there pivotal moments that lead to shifts in character interactions?
6. Character Alliances: Discover alliances and enmities among characters by identifying clusters within the network. Are there unexpected connections between characters that reveal hidden story elements?
7. Narrative Structure: Analyze the network to understand how character interactions drive the narrative. Which interactions are critical in advancing the plot, and which are more peripheral?

By delving into the character interaction networks of the Harry Potter series, you can uncover hidden layers of storytelling and gain a deeper appreciation for the rich tapestry of relationships woven by J.K. Rowling. This data is a treasure trove for both fans and researchers, providing new avenues to explore the magic of the wizarding world.

The project to create character interaction networks for the Harry Potter series was inspired by the work presented by [Andrew Beveridge](https://twitter.com/mathbeveridge) on the "[Network of Thrones](https://networkofthrones.wordpress.com)" project, which focuses on character interactions in the "A Song of Ice and Fire" series. Andrew Beveridge's work on character networks in literature served as the inspiration for this project, showcasing the potential of network science in uncovering hidden dynamics within beloved fictional universes.

## Data Files

### Edge lists
The edge list files contain information about the interactions between characters in each book of the series. These files are used to build the character interaction networks. Each line in an edges file represents a connection (edge) between two characters, and the edge weight corresponds to the number of interactions between them. Here's a description of the structure:

- **source**: The character initiating the interaction.
- **target**: The character with whom the interaction occurs.
- **weight**: The frequency or strength of interactions between the source and target characters.

### Characters
The [characters.csv](./data/characters.csv) file contains information about the first appearance of each character in the series. It includes two columns: "book_chapter" and "character," specifying the book and chapter in which each character makes their debut.