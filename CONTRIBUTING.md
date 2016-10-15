# Contributing to the DevelopFreedomMod #

## Rules ##
Avoid using org.bukkit.Server.dispatchCommand(). Commits that make use of it will likely be rejected.
PRs must only address issues which are marked as "accepted", "bug", or "needs pull request". 
PRs should only address one issue per PR, not several. Several is allowed.
PRs must not solely be grammar fixes, config-edits, small changes (less than 10 lines of code) or message rephrasing edits. Small edits such as these take very little effort to make and a lot more effort to review and integrate into the codebase.
PRs should be compiled and tested before they are submitted. If your PR does not function or has clearly not been tested, it may be closed without notice.

## Tips to get a suggestion accepted ##

Please make sure your changes are written such as other features would be. For example, commands have their own class and extend FreedomCommand.
Do not increment the version number.
Please avoid having to add files in the main namespace where possible.
Please refrain from using an excessive amount of commits. As few as possible is generally the best.
Please do not spread your contribution over several pull-requests.
