<h1 align="center">Noire UI</h1>

<p align="center">Design system used by <a href="https://guale.dev/">Flowframe</a></p>

<h3 align="center">
  <a href="https://storybook.guale.dev/">Storybook</a> -
  <a href="https://www.figma.com/design/">Figma UI kit</a> -
  <a href="https://github.com/noahguale/noire-ui">Source Code</a>
</h3>

## Getting Started

Install Noire UI:

```sh
$ pnpm add noire-ui
```

Import the global CSS file at the root of your application:

```tsx
import 'noire-ui/styles.css'
```

Add the Theme component:

```tsx
import { Theme } from 'noire-ui'

export default function () {
	return (
		<html>
			<body>
				<Theme>
					<MyApp />
				</Theme>
			</body>
		</html>
	)
}
```

## Acknowledgments

Noire UI is heavily based on [shadcn](https://ui.shadcn.com/) and [Radix Themes](https://www.radix-ui.com/) design system and [Lucide ](https://github.com/lucide-icons/lucide/).
