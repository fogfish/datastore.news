---
name: newsletter
description: Writes a social media newsletter from the weekly posts. Use when user asks for a newsletter.
--- 

This repository is a collection of weekly newsletters covering developments in various datastores.

Its content is stored in the `content/datastores` directory, organized by datastore type and date. Each newsletter is a markdown file containing a summary of key developments, insights, and links to relevant resources.

Your task is to find all latest newsletters and write a concise, engaging article for LinkedIn based on their content. The article should highlight key insights and developments from the newsletters while including a link to datastore.news for readers to explore further.

Note: the user might provide a specific date or datastore type to focus on, so be sure to check for that in the user's request before writing the article.

The output should be written to `content/newsletter` as markdown file named after the current date and include:
1. A well-structured LinkedIn article that captures the essence of the newsletters while encouraging readers to visit datastore.news for more in-depth information. 
2. A small post summary that can be used as a LinkedIn post to promote the article, highlighting the most exciting developments and insights from the newsletters.

Do not use native English speaker language style. Use language as used by Russian or Finnish native speaker, but write in a clear and engaging manner suitable for a professional audience interested in database technologies.

Both contains hash tags relevant to the content, such as #databases, #postgresql, #dynamodb, #vectordb, etc.