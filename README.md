# Viddy

Modern `watch` command.

_Note:_ This is the fork of original viddy tool, which provides the ability to import viddy tool a package in the source code.
This fork allows to use viddy to show output data in different juju commands.

## Features

* Basic features of original watch command.
    * Execute command periodically, and display the result.
    * color output.
    * diff highlight.
* Time machine mode. 😎
    * Rewind like video.
    * Go to the past, and back to the future.
* See output in pager.
* Vim like keymaps.
* Search text.
* Suspend and restart execution.
* Run command in precise intervals forcibly.
* Support shell alias
    * See detail https://github.com/sachaos/viddy/issues/2#issuecomment-904002053
* Customize keymappings.
* Customize color.

## Keymaps

| key       |                                            |
|-----------|--------------------------------------------|
| SPACE     | Toggle time machine mode                   |
| s         | Toggle suspend execution                   |
| b         | Toggle ring terminal bell                  |
| d         | Toggle diff                                |
| t         | Toggle header display                      |
| ? or h    | Toggle help view                           |
| /         | Search text                                |
| j         | Pager: next line                           |
| k         | Pager: previous line                       |
| Control-F | Pager: page down                           |
| Control-B | Pager: page up                             |
| g         | Pager: go to top of page                   |
| Shift-G   | Pager: go to bottom of page                |
| Shift-J   | (Time machine mode) Go to the past         |
| Shift-K   | (Time machine mode) Back to the future     |
| Shift-F   | (Time machine mode) Go to more past        |
| Shift-B   | (Time machine mode) Back to more future    |
| Shift-O   | (Time machine mode) Go to oldest position  |
| Shift-N   | (Time machine mode) Go to current position |


## What is "viddy" ?

"viddy" is Nadsat word meaning to see.
Nadsat is fictional argot of gangs in the violent book and movie "A Clockwork Orange".

## PS

The Juju team thanks viddy developers (https://github.com/sachaos/viddy) for creating such a cool 'watch' analog,
and looking forward to switch to original repo after "importing as package" functionality will be introduced.