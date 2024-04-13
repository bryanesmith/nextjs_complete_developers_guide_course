# Next JS: The Complete Developer's Guide notes

Notes and projects from [Next JS: The Complete Developer's Guide](https://www.udemy.com/course/next-js-the-complete-developers-guide) on Udemy.

## Notes

See: `notes/section_*.md`

## Projects

| folder | section(s) | Description | key concepts |
| ------ | ------- | ----------- | ------------ |
| `corp/` | 1 | Static corporate website | Next.js file based routing, `Link`, layouts with `layout.tsx`, reusable components, `Image` |
| `snippets/` | 2 - 6 | CRUD app for managing code snippets | SQLite, Prisma library, Server Action, redirects, dynamic paths, notFound, custom 404 pages, custom loading pages, server vs client components, React Monaco Editor, React state, useFormState, custom error pages  |

## Key concepts

| Name | Purpose |
| ---- | ------- |
| `page.tsx` | Displays the primary content for the page |
| `layout.tsx` | Wraps the currently displayed page. Use to show content common across many pages. |
| `not-found.tsx` | Displayed when we call the `notFound` function |
| `loading.tsx` | Displayed when a server component is fetching some data |
| `error.tsx` | Displayed when an error occurs in a server component |
| `route.tsx` | Defines API endpoint |

