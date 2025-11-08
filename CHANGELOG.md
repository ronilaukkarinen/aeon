### 1.1.0: 2025-11-08

* Fix alignment for join/part/quit/kick/mode/topic messages to match chat messages
* Use 9-char nick field for messages with ` ●` separator to align with 10-char + `>` chat format
* Change action messages (/me) to bright yellow for nick, bullet, and text
* Fix action message formatting to properly display nick with space before bullet
* Change private message separator from `|` to `>` to match public chat format

### 1.0.0: 2025-11-08

* Initial release of Æon theme
* Convert all headings to sentence case
* Unify status message colors with actions in color and details dimmed
* Align all nicks (chat, join/part/quit/kick/mode, /me actions) in nick column
* Remove indenting from status messages
* Fix color codes (dim grey %K instead of black %k)
* Modernize comments and remove outdated version references
