# The Binary Architect

Personal blog built with plain HTML + JS, hosted on GitHub Pages.

## Adding a post

1. Create a file in `blog/` named `MM-YYYY_Title.html`
2. Add the path to the `POSTS` array in `index.html`
3. Include a keywords line somewhere in the post body:
   ```
   keywords: tech, writing
   ```

## Drafts

Add `draft` to the keywords and the post won't appear on the index — but you can still visit it directly by URL.

```
keywords: tech, draft
```

Remove `draft` when you're ready to publish.
