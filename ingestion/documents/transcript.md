---
aliases: [meeting transcript, VTT file]
broader: ingestion/documents/document.md
---
# Transcript

The timed text of a meeting, a `.vtt` file that a [reader](reader.md) turns into [cues](cue.md) with their timecodes. Its words enter the search index and the occurrence scan once [pseudonymisation](../sources/pseudonymisation.md) has run, a mention read in it cites its timecode, and it is often a [twin resource](../sources/twin-resources.md) of the deck and the notes of the same meeting. A transcript is indexed only when the configuration publishes transcripts explicitly.
