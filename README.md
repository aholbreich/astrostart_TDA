# Astro + TDA project stater

* **T**ailwind
* **D**aisyUI
* **A**lpineJS

A minimalistic Astro project starter that includes Astro 5, Tailwind 4 with DaisyUI 5. In terms of JavaScript this project include **Apline.js**.

The purpose is the demonstration of the integration of the [listed Dependencies](#Dependencies) eg. Tailwind 4. 
Also, it includes a few example components. Like functional opinionated mobile-first navigation component and _floating menu_ and SEO component to be used in Layouts.


TODO: [Live Demo](https://astro-start-tailwind.vercel.app/)

## Usage

Bootstrap your new project using this template with:

```bash
pnpm create astro@latest --template aholbreich/astrostart_TDA
```

Alternatively clone this repo and just start coding. The following commands should be helpful:

### Commands

All commands are run from the root of the project, from a terminal:
I'm in favor of `pnpm` but `pnpm` and yarn would work as well.

| Command                 | Action                                           |
| :---------------------- | :----------------------------------------------- |
| `pnpm install`          | Installs dependencies                            |
| `pnpm dev`              | Starts local dev server at `localhost:3000`      |
| `pnpm build`            | Build your production site to `./dist/`          |
| `pnpm preview`          | Preview your build locally, before deploying     |
| `pnpm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro --help` | Get help using the Astro CLI                     |

if  `pnpm preview`  is not working for you, you can workaround with:

```bash
pnpm build
pnpm dlx serve dist
```

## Dependencies

- Astro 5.6
- Astro Icon
- Astro SEO
- Astro MDX
- Tailwindcss 4
- Daisy UI 5
- Alpine.js
- Netlify

## Configuration & Customization

Simple configuration can be found in `src/lib/config.ts`
There are just a few demonstration components, you can delete them, ignore them, adapt them whatever fist you.

## Collaboration

Feel free to provide your feedback or feature requirements.

### TODO

* More Alpine.js examples, docu