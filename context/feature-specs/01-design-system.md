Read `AGENTS.md` before starting

We are adding the design system and UI Primative components.

Install and configure `shadcn/ui`.

Add these shadcn components

- Button
- Card
- Dialog
- Input
- Tabs
- Textarea
- ScrollArea

Do not modify the generated `components/ui/*` files after installation.

Also install `lucide-react`.

create `lib/utils.ts` with a reusable `cn()` helper for merging Tailwind clases

Ensure all the components match the exixting dark theme in `global.css`

### Check when is done
- All components import withou errors
- `cn()` works properly
- no default light styling appears
