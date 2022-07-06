# Contributing guidelines

To measure extension popularity, one thing that we must ask of you is that **each one of your extensions is developed within a repository of its own**.

## Before contributing

An extension name should consist of one word starting with an uppercase letter and shouldn't contain `spicetify` or any whitespace in it; if a "-" is present in the name it must be followed by an uppercase letter.

## How to contribute

If you want your extension to show up on **Spicetify Marketplace**, you will need to create a Pull Request to this repository with the following structure:

```
.
├── ...
├── Extension_name              # Folder with your extension name.
│   ├── screenshots             # Folder with extension screenshots.
│   ├── manifest.json           # Manifest file with the structure detailed below.
│   └── README.md               # Readme file with the extension description.
└── ...
```

For this, you'll need:

1. Fork this repository
2. Create another folder named after your extension name
3. Create a `README.md` in it with the following structure

   ```markdown
   # Extension Name

   Description of your extension.

   ## Screenshots

   [Put at least one image here]

   ## More

   [Specify any needed font; (optionally) author name and/or any other info about the extension]
   ```

> _Note_: All screenshots must be in PNG format and, additionally, must be uploaded to this repository.

4. Commit only once, more details in the **Commit Message**
5. Open a Pull Request and mention the most important changes you've made to the UI (ignoring the color scheme)

**Thanks to all the contributors.**

## Commit Message

### Format

    <type>(<scope>): <subject>
    <BLANK LINE>
    <body>[optional]

**Any line of the commit message cannot be longer than 100 characters!**

- **type:** feat | fix | docs | chore
  - **feat:** A new extension | A new scheme | A new feature
  - **fix:** A bug fix
  - **docs:** Change the `README.md` of the extension
  - **chore:** Add more screenshots | Change the screenshots | Other things
- **scope:** `<ExtensionName>`
- **subject:** What changes you have done
  - Use the imperative, present tense: "change" not "changed" nor "changes"
  - Don't capitalize the first letter
  - No dot (.) at the end
- **body**: More details of your changes, you can mention the most important changes here

### Example (Wikify extension)

- feat

  ```
  feat(Wikify): add Wikify extension
  ```

  ```
  feat(Wikify): support for different fonts
  ```

- fix

  ```
  fix(Wikify): show the cursor outside the context menu
  ```

- docs

  ```
  docs(Wikify): update README.md
  ```

  ```
  docs(Wikify): add preview for the Wikify
  ```

- chore

  ```
  chore(Turntable): update supported versions
  ```

  If you want to learn more, view the [Angular - Git Commit Guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines).
