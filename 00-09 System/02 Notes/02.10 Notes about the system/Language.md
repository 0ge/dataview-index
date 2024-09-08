# Language

One realization that has come to me is that the language you choose to have your system in is important. The reason is that when you search, you have to choose keywords and if you don't know what language it is in, you have to do a search per language.

At the same time, you want something that is natural. Taking notes about your house in English is unnatural. Similarly, taking notes about programming in Swedish is also difficult. It also makes it more difficult to search, as some keywords must be in English.

Therefore, the following method has been chosen. 

- *Basic language is Swedish*, which means that if nothing else is selected, Swedish will be used.
- *The language can be changed down the hierarchy*. If a category is named in English, all the underlying IDs, notes, files, etc. must also be in English.

Example:
- [[40-49 Hobby och fritid]]
	- [[44 Software and hardware]]
		- [[44.01 Books on software development]]
		- [[44.02 Architecture]]

So everything under [[44 Software and hardware]] is in English.

There are two exceptions:
 - If an external file is in another language, it may of course remain in that language.
 - Metadata is defined at “global level” and may follow that practice. For example, `category` is used in frontmatter for Index notes (because it is “programming”), and Index notes are always in Swedish, even if the note is about something in English.
