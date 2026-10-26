---
name: search-procedure-en
description: Read this before any search (code, papers, products, documents, personal notes — any work that involves searching through content). A procedure that structures what you want to do or know by separating the parts that would make it something else if dropped from the parts that are only one way of doing it, decides what you should be looking for, and then searches with terms derived from that structure. It finds existing things even when you know neither their names nor how they work, and when nothing is found, it narrows the cause to either a mistake in deciding what to look for or the thing not existing yet. Not for browsing by name or heading alone to pick out something close. It does not cover the operation of any particular search interface or query syntax.
---

## Purpose

Structure what you want to do or know and search across a wide range, so that you can find things even when you know neither their names nor how they work.

If you search with the words that come to mind as they are, anything that doesn't contain those words won't appear in the results. What doesn't appear never shows up on the screen, so you can't notice that it was left out. You miss what you're looking for just because it was written in other words or used a different method. And when nothing is found, you can't say it doesn't exist, because it may only have been phrased differently.

So search in two stages.

1. Structuring: split the description into what the thing you're looking for does (the structure) and the conditions it must meet that would make it something else if dropped (the core). Names of means, which are only one way of doing something, are replaced with what they do and put into the structure. This decides what you're looking for by "what it is and what it does," not by name.
2. Querying: for each part of the core and the structure, derive as many terms as you can that are likely to actually be written where you search, and search with them. From the structure, also derive other ways of doing it. The search string is not a shortened description; it is derived from the structuring. However, terms that come to mind right away stay within the wording you already know. If nothing is found with these near terms, map the structure to things in distant fields that have the same relation (far analogy), and also search with the wording used in those fields.

Write out the structuring and check it before moving on to querying. If the structure is wrong, every search string derived from it will be off.

This way you can find existing things even when you know neither their names nor how they work. When nothing is found, the cause narrows to either a mistake in deciding what to look for or the thing not existing yet.

During structuring, don't come up with other forms or other methods that aren't in the description. Structuring is organizing your current thinking; coming up with other methods is the job of querying.

## Example

What you want: "a browser extension that uses yt-dlp to automatically save arbitrary videos to Google Drive." Look for an existing tool that does this on the web and on extension stores.

### Structuring

The words in the description are: extension, yt-dlp, Google Drive, automatically save.

- automatically save: this is what the thing does, so it is structure. "Save automatically."
- extension: drop it and you would also be looking for things that aren't extensions, which departs from what you want. Core.
- Google Drive: drop it and you would also be looking for things that save somewhere other than Drive, which departs from what you want. Core.
- yt-dlp: what it does is take the video content from a page. Taking it some other way would still satisfy what you want. It is a means, so replace it with "take the video content" and put that into the structure. Searching with "yt-dlp" as is only hits things that use yt-dlp.

Core: is an extension; saves to Drive. Structure: take the video content; save automatically.

### Querying

Wording like "take the video content" is often not written in tool descriptions, and if it isn't, you won't hit the tool even if it exists. For each part of the core and the structure, derive as many terms as you can that are likely to appear in a tool's name or description.

- is an extension → extension, add-on, browser extension, etc.
- saves to Drive → Google Drive, etc.
- take the video content → other ways of doing it (yt-dlp, youtube-dl, m3u8, etc.) and words for the act of taking itself (download, downloader, save video, etc.)
- save automatically → auto save, auto-save, upload, etc.

Require at least one of the derived terms for each of the two core parts and the two structure parts, and search for things that satisfy all four. Look first at results in which many of the derived terms appear. You don't need to know the names of what you will find, or ways of taking video other than yt-dlp, before searching.

### Far analogy

If nothing is found with near terms, extract the structure as a relation. Here, take "take the video content" as the example: copying something that flows by, on the receiving side. List things in distant fields that have the same relation, and derive the wording used in those fields.

- Broadcast recording: recording a program that flows in, on your own side → recorder, capture, etc.
- Network interception: copying the content of passing traffic from the side → sniffer, sniff, etc.

Keep the extension and Drive terms required, and add these terms to the "take the video content" part. This hits tools that do the same thing even if they don't call themselves video downloaders. Check whether what you hit can actually take video when you look at it.

## Procedure

Terms used in this section:

- Description words: the words that appear in the sentence describing what you want to do or know (in the example, "extension," "yt-dlp," "Google Drive").
- Core: the conditions the thing you're looking for must meet that would make it no longer the thing you're looking for if dropped (in the example, "extension" and "Google Drive"; for "a method for finding people's ideas through far analogy," "people's ideas," "far analogy," and "method"). Don't put these into the structure; use them as search conditions as they are.
- Means: something that is only one way of doing the same thing (in the example, "yt-dlp").
- Structure: what the thing you're looking for does. Include both what is written as an action in the description (in the example, "save automatically"; in the case above, "find") and what replaces a means (in the example, "take the video content"). Far analogy maps only this part.

### Structuring

1. Write out the words that appear in the description of what you want to do or know.
2. Split the description words into what the thing does (actions) and everything else. Actions become structure. For everything else, ask "if I drop this word, is it no longer the thing I'm looking for?" and split it into core and means. The structure is decided by whether something is an action, because leaving it to the judgment of whoever is searching leads to misjudging what the structure is.
3. Replace each means with what it does and put that into the structure. Searching with the name of a means only hits things that use that means.
4. Don't add conditions that aren't in the description (language, era, place, etc.). Adding them drops things from the results that are what you're looking for but don't meet the condition. "Language" here means a condition that restricts results to a particular language; which language to write terms in is decided in step 5. Write out the core and the structure and check them before moving on to querying.

### Querying

5. For each part of the core and the structure, derive as many terms as come to mind right away that are likely to actually be written where you search. The wording of the description ("something like ~," "automation," etc.) is often not written where you search, and if it isn't, you won't hit what you're looking for even if it exists. What you derive are the things a person checks when reviewing candidates one by one (file names, setting names, APIs, a paper's method names, a product's screens or settings, a document's terms or headings, etc.). If the form of what you're looking for (an extension, a paper, etc.) is fixed in the description, include what is always written in things of that form; this narrows the search without dropping what you're looking for. From the structure, derive other ways of doing it, not limited to names in the same family, and include the original name of the means too. Also include words for the action itself, so that methods whose names you don't know still hit. Write terms in the language that the place you search is written in. If you don't know that language, write them in several languages.
6. Require at least one of the derived terms for each part of the core and the structure, and search for things that satisfy all of them. With searches where you can't specify AND/OR (web search, etc.), run several search strings that line up terms from the core and the structure, changing the combination. Don't try too many combinations at once; match the number to how hard the search is, and decide the next combinations after looking at the results.
7. Look first at results in which many of the terms derived in steps 5 and 8 appear. Since step 6 already makes every result satisfy all parts of the core and the structure, what makes the difference is how many terms hit. Because you search widely, there will be many results. Don't narrow the range you look at first by adding conditions; narrow it by the order in which you look.
8. If nothing is found with near terms, or near terms seem unlikely to hit, derive terms by far analogy. Extract the structure as a relation of "what, and what is done to it," and list things in distant fields that have the same relation. Add the wording used in those fields to the "any of" set for the structure, and search. Don't map the core; keep the core terms required. Mapping the core too would change what you're looking for. Near terms that come to mind right away stay within the wording you already know, so they don't hit things made in another field under another name. Whoever is searching lists the distant things from their own knowledge.

### If nothing is found

9. Review how you decided what to look for. Check whether what you made core really can't be dropped (whether you mistook a means for core and narrowed too much), and whether the terms derived in steps 5 and 8 match how the place you search is written. If a core part turns out, in light of the purpose, to have been unnecessary, don't remove it from the conditions; widen it to the range that still serves the purpose, and search again (for example, if no method for finding people's ideas through far analogy is found, anything that can serve as a hint will do, so widen "people's ideas" to "existing structures"). Removing it from the conditions leaves undecided what the action in the structure is directed at (in the example, what is being searched for).
10. If you still find nothing after reviewing, conclude that it doesn't exist yet.

### When presenting results

11. Present the result of structuring (the core and the structure) together with what you found. If the structure is wrong, the whole search is off, so this lets the user check whether what to look for was decided correctly.

## Rules of thumb

- Form (an extension, etc.), storage destination, and scope of the target, if dropped, often make it no longer the thing you're looking for, so they tend to be core.
- Tool names, library names, and specific technique names often point to just one way of doing the same thing, so they tend to be means. But sometimes the name itself is the core of what you're looking for. Don't sort mechanically by category; decide with the question in step 2.
