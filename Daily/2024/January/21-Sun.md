
# 2024-01-21

## Obsidian Tasks

- [x] Complete new obsidian setup for personal notes
	- [x] Document plugins used and settings
- [x] Integrate Github pages blog as sub-module
	- Also doesn't need to be a submodule since you can publish a pages site from any repo apparently, just have to check if it uses the correct URL
	- I lied it does need to be a submodule
	- I ended up using a dark mode theme for Jekyll that builds right from my notes
- [x] Upload and store personal library, link as sub-module in notes
	- We can do this through a simple Library subfolder within the Reference section that contains a copy of my library.... it doesn't actually have to be a submodule I think

## Other 
- [x] Update github profile
	- [x] Remove stale repos
	- [x] Upload notes
	- [x] Keep bio and other information up to date
- [x] Update linkedin information if required
	- [x] Update tagline and interests to reflect what I am currently interested in
	- [x] Add skills if there is anything new to add
- [x] Create a reading list in obsidian to include both nonfiction and fiction titles
	- [[../../../Resources/Reading List/Nonfiction/Software]]
	- [[../../../Resources/Reading List/Fiction/Fantasy]]

## Notes

#journal I've been experimenting with Golang recently, and have only just not encountered something I dislike. Because of the way that slices and arrays are structured removing an element without a full data copy is a PITA. I suppose you could use a linked list but I'd also have to implement that myself. I understand the premise of having a barebones Standard library but at times it feels like Golang takes it to far.



#### Notes Modified Today
```dataview
list
WHERE datemodified = this.file.day or datecreated = this.file.day 
```
