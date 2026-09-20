# Open Path for Alfred

Open a file path, folder path, or URL from Alfred.

## Usage

1. Invoke Alfred and enter `go ` followed by a path or URL.
2. Press Return once.

Folders open in Finder. Files are revealed and selected in Finder without opening their associated application. URLs open with macOS's default handler. Invalid paths show an alert.

## Source

`src/info.plist` is the workflow definition. The local `Open Path.alfredworkflow` export is deliberately ignored by Git and can later be attached to a GitHub Release for installation.
