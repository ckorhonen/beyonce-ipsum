# Working on beyonce-ipsum

Despite the repository name, this snapshot documents the Bacon Ipsum generator.
`gga-BaconIpsumGenerator.php` contains the standalone generator; the other PHP
files provide WordPress form, API, and oEmbed plugins. `jquery-sample.html` is a
browser example. Preserve public method names and existing plugin conventions.

There is no package manifest or automated suite. Run `php -l <changed-php-file>`
for syntax, then exercise generator changes with a small local PHP example based
on README. Plugin integration requires a disposable WordPress installation;
loading plugin files alone does not prove WordPress behavior. Browser examples
can contact remote APIs, so use local fixtures for routine checks. Report syntax,
generator behavior, and WordPress/browser verification separately.

## Completing changes

Follow existing patterns and carry authorized work through the relevant checks,
repairing failures caused by the change. Choose routine implementation details
directly; ask only when missing information materially changes scope or outcome.
For documentation-only edits, check the diff, referenced paths, and command
accuracy rather than starting application runtimes. If a prerequisite blocks a
check, report the exact blocker and continue independent authorized work. Close
with changed paths, checks actually run and results, and remaining unverified
behavior; distinguish commands inspected from commands executed.
