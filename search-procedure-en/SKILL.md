---
name: search-procedure-en
description: Read this before any search (code, papers, products, documents, personal notes — anything that involves searching through content). Use it when what you're looking for is already decided and you're searching for something that already exists. Not for browsing by name or heading alone to pick out something close. It's a procedure for deciding which search terms to make required and which to drop; it does not cover the operation of any particular search interface or query syntax.
---

Read this before searching. It applies regardless of where you search: code, papers, products, documents, personal notes — any work that involves searching through content.

What this decides is which words to make required and which to drop. It does not cover the operation of a particular search screen, nor query syntax.

## Scope

Use this when what you're looking for is already decided and you're searching for something that already exists. Not for browsing by name or heading alone to pick out something close.

## Principles

Enter one search term, and anything that doesn't contain that term drops out of the results. Searching is both a matter of hitting the target and a matter of deciding what you won't see. What to check first isn't what remains, but what drops out.

The words that appear in a description split into two kinds:

1. Words that, if dropped, mean you're no longer looking for the thing you wanted
2. Words that just name one particular means of doing the same thing

Keep type 1. For type 2, if the same thing can be said to exist via a different means, and there's no need to see it in the first search, drop it. Don't throw away the dropped name — keep it as a candidate for when you search for the same thing again.

Form, storage location, and scope of the target tend to be type 1. Drop "extension," and background programs get mixed in. Drop the storage location, and other storage locations get mixed in. Drop the target/scope, and it becomes a different problem. It's not that another form doesn't exist — but if what you're looking for is that particular form, then search limited to that form first.

Tool names, library names, and specific technique names tend to be type 2. Keep them, and other ways of writing the same thing drop out of the results. But sometimes the name itself is the very thing you're looking for. Don't sort mechanically by category — the standard is always: "does dropping this word mean it's no longer the thing I'm looking for?"

Language, era, and location work the same way. If nothing was specified, don't make it a condition from the start. Adding it can drop things from the results that actually satisfy the condition.

The way you'd phrase it in your head won't hit. What hits is only the words actually written in the target. Phrases like "something like ~" or "automation" often don't appear in the target itself. Replace them with the clues a person would actually check when reviewing candidates one by one: file names, setting names, APIs, a paper's method name, a product's screens or settings, a document's terminology or headings. If the form is already fixed, narrow first using clues specific to that form.

Don't try to see every candidate in the first search. Leave only the range you need to see right now. Look at other forms only after you haven't found it.

Even if you don't find it, don't loosen all the initial conditions at once. Loosen the dropped ones one at a time, in order of how likely you need to see them. Adding to the original search string makes it unclear what actually caused the hit.

## Procedure

1. Write out the words that appear in the description of what you're looking for.
2. For each word, check in this order:
   1. If you keep this word, what drops out of the results?
   2. Is it fair to call what drops out "the thing you're looking for"?
   3. If it's fair, do you need to see it in the first search?
3. If the answers to 2 and 3 are both yes, drop the word. Search based on what that part does. Keep the original name as a candidate. Otherwise, keep it. Write down the dropped alternate forms, in the order you'd loosen them later.
4. Replace the words you kept with the clues that actually appear in the target you're searching now. If the form is already fixed, narrow using that form's clues first.
5. For the parts you dropped, enumerate the means that accomplish the same thing. Not limited to names in the same family or lineage.
6. Build the first search string. Make all the kept words required. The dropped parts can be satisfied by any of the enumerated means.
7. Among the required conditions and the means, look first at whichever has the most matches.
8. If you don't find it, loosen the dropped conditions you wrote down, in order of how likely you need to see them. Don't add them to the first search string.

## Example

What you're looking for is: "a browser extension that uses yt-dlp to automatically save arbitrary videos to Google Drive." Whether the search target is code, a product, or an article, the way you split it up is the same.

Drop "extension," and background/resident programs get mixed in. For this content, there's little need to look there from the start. Keep it. The clue is whatever appears inside something that is, in fact, an extension.

Drop "Drive," and other storage destinations get mixed in. If the storage destination you want is Drive, then search limited to Drive first. Keep it. The clue is the name or API that appears when outputting to Drive.

Keep "yt-dlp," and ways of fetching the video other than by that name drop out of the results. If the task is just fetching the actual video content, another means will do. Drop it. Search based on what it does. yt-dlp itself remains one candidate.

In the first search, make the "it's an extension" clue and the "outputs to Drive" clue both required. The way of fetching the video can be satisfied by any of the enumerated means. If that doesn't turn anything up, add things like background/resident programs — the dropped forms — in order of how likely you need to see them.

The search string is not a summary of what you're looking for. It's the result of first separating what's fine to drop from what must not be dropped.
