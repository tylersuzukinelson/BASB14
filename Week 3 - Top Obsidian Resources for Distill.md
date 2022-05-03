# Week 3 - Top Obsidian Resources for Distill

## TLDR

Distillation is all about increasing the signal-to-noise ratio of your notes (i.e. increasing their value density). There are many ways to do this including progressive summarization, using metaphors, or duplicating ideas into atomic notes; it's important to find a way that works for you with your own notes. It's also important to remember that distillation should take place just-in-time, with a specific goal in mind.

## Mentor sessions

- [Billy Broas](https://building-a-second-brain.circle.so/c/mentor-sessions/billy-s-april-29th-mentor-session-highlights-recordings)
- [Bob Doto](https://building-a-second-brain.circle.so/c/mentor-sessions/bob-s-april-28th-mentor-session-3-distill)
- [Frank Anaya](https://building-a-second-brain.circle.so/c/mentor-sessions/frank-s-mentor-session-3-distill-week-4-30-22)
- [James Stuber](https://building-a-second-brain.circle.so/c/mentor-sessions/james-mentor-session-3-distill-week-5-1)

## Progressive summarization

- Part of the reason note-design is important is because your notes are probably the most resilient part of your PKM. If a plugin is ever retired, you won't be able to interact with your notes in the same way (e.g. your [dataview](https://github.com/blacksmithgu/obsidian-dataview) queries will appear as they do in the editor view instead of pulling in the results you expect them to). If Obsidian is ever retired, certain formatting will no longer display as expected (e.g. [callouts](https://help.obsidian.md/How+to/Format+your+notes#Callouts)). (However, any editor that can render markdown can still parse your bolded and highlighted notes for you.) Even links can go out of date quickly--Obsidian makes things like renaming files convenient, but remembering to update all your backlinks manually without Obsidian can be easy to forget.
- [Progressive summarization](https://fortelabs.co/blog/progressive-summarization-a-practical-technique-for-designing-discoverable-notes/) is a technique to compress your notes. Another technique to compress your notes is by using metaphors.
- Progressive summarization is done to help you in some way (e.g. making value more accessible, making notes more helpful for your projects). It's important to keep that goal in mind when you're distilling your notes (otherwise, you may just be doing busy-work). Use that goal to determine what you're going to bold, highlight, and/or summarize as you review your notes.
- You don't need to progressively summarize a note all at once for the sake of distilling it. Progressive summarization should be done on a just-in-time basis--when you need to use the note for some purpose. Sometimes the process of progressive summarization will take place over multiple sessions--perhaps with days or weeks in between. And if you add one layer each time you distill a note, it can naturally allow the most resonating sections to bubble to the top organically.
- Your progressively summarized notes are intended to help you. Notes on topics that you're already deeply familiar with may not have very many highlights because you already know a lot of what was discussed. For notes on more novel, foreign, or uncomfortable topics, you may have many more highlights; your progressive summarization may even be longer than the original source as you do the work to make the note helpful to future you.

## Obsidian tips

- To make text **bold**, wrap it in double asterisks.
- To ==highlight== text, wrap it in double equal signs.
- To bold or highlight text:
    - Select/highlight the text in your editor view.
    - Press the `*` key twice to bold it, or press the `=` key twice to highlight it.
- You can [set hotkeys (keyboard shortcuts)](https://help.obsidian.md/Customization/Custom+hotkeys#Setting+hotkeys) for bolding or highlighting text in the `Settings > Hotkeys` section. The hotkeys you are looking for are called `Toggle bold` and `Toggle highlight`.
- The below [query block](https://help.obsidian.md/Plugins/Search#Embed+search+results) will show you how to embed a search for highlighted text within your vault:
```query
/==.*?==/
```
- You can use a callout to add a summary (i.e. level 4 of progressive summarization) to your notes:
> [!SUMMARY] Mini-summary
> A short summary of the source that may include your own thoughts on the topic.
- Depending on how you use your notes, it may be useful to have one file for each source where you keep your main progressive summarization, and then copy certain quotes or ideas from that source note into their own note. This smaller note can then be linked or [transcluded](https://help.obsidian.md/How+to/Link+to+blocks#Embed+or+transclude+blocks) in other notes to reveal relationships between other notes that relate to this specific quote or idea.

## Notable plugins

- [cMenu Plugin](https://github.com/chetachiezikeuzor/cMenu-Plugin)
- [Obsidian Markdown Formatting Assistant](https://github.com/Reocin/obsidian-markdown-formatting-assistant-plugin)
- [Highlightr-Plugin](https://github.com/chetachiezikeuzor/Highlightr-Plugin/)

## Miscellaneous

- Reminder that for that first layer of progressive summarization, even if you don't use a tool that lets you export your highlights (e.g. [Instapaper](https://www.instapaper.com/), [Readwise](https://readwise.io/), [Kindle + bookcision](https://readwise.io/bookcision)), you can always manually cut and paste.

## Additional resources

- There were two conversations in Circle about how to bold and highlight text in Obsidian for the purpose of progressive summarization (i.e. [here](https://building-a-second-brain.circle.so/c/obsidian-3f8b75/distill-in-obsidian), [here](https://building-a-second-brain.circle.so/c/obsidian-3f8b75/best-practices-for-distill-using-obsidian-markdown)).
- Here is the [distill summary](https://building-a-second-brain.circle.so/c/roam/week-3-top-roam-obsidian-resources-for-distill) from cohort 13.