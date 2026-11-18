# the hickerlab website

Each page of the site is one text file:

| Page | File |
|---|---|
| Home (welcome, research, news, contact) | `index.md` |
| People | `people.md` |
| Software & Teaching | `teaching-software.md` |
| Older news | `news-archive.md` |

## To change something

1. Click the file in the list above.
2. Click the pencil icon (top right of the file).
3. Change the words.
4. Click **Commit changes**. The live site updates in a minute or two.

## Common edits

**Add a news item.** In `index.md`, add a line at the top of the list under `## News`:

    - **March 2027.** What happened.

**Add a person.** In `people.md`, copy one of the entries under `## Current` and change the name and text. To move someone to alumni, delete their entry and add one line under `## Alumni`.

**Add a photo.** Open the `images` folder, click **Add file**, then **Upload files**. Square-ish photos work best. Then point to it from `people.md` like the other entries: `![Name](images/filename.jpg)`.

**Add a course.** In `teaching-software.md`, add a line at the top of the list under `## Teaching`.

## Things you can leave alone

`_config.yml`, `_layouts/`, and `assets/style.css` control the look. They never need touching for normal updates.
