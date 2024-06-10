<div align="center">
  <a href="https://www.@taktikorg/atque-tempore-provident.com">
    <img alt="@taktikorg/atque-tempore-provident" src="https://raw.githubusercontent.com/@taktikorg/atque-tempore-provident/brand/master/@taktikorg/atque-tempore-provident.png" height="150px" />
  </a>
</div>

<br />

<div align="center">
  <strong>Visual primitives for the component age. Use the best bits of ES6 and CSS to style your apps without stress 💅</strong>
  <br />
  <br />
  <a href="https://www.npmjs.com/package/@taktikorg/atque-tempore-provident"><img src="https://www.@taktikorg/atque-tempore-provident.com/proxy/downloads.svg" alt="downloads: 600k/month"></a>
  <a href="#backers" alt="sponsors on Open Collective"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/backers/badge.svg" /></a> <a href="#sponsors" alt="Sponsors on Open Collective"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsors/badge.svg" /></a> <a href="https://discord.gg/hfGUrbrxaU">
        <img alt="Discord" src="https://img.shields.io/discord/818449605409767454?logo=discord" /></a>
  <a href="https://bundlephobia.com/result?p=@taktikorg/atque-tempore-provident" title="@taktikorg/atque-tempore-provident latest minified+gzip size"><img src="https://badgen.net/bundlephobia/minzip/@taktikorg/atque-tempore-provident" alt="gzip size"></a>
  <a href="#alternative-installation-methods"><img src="https://img.shields.io/badge/module%20formats-umd%2C%20cjs%2C%20esm-green.svg" alt="module formats: umd, cjs, esm"></a>
  <a href="https://codecov.io/gh/@taktikorg/atque-tempore-provident/@taktikorg/atque-tempore-provident"><img src="https://codecov.io/gh/@taktikorg/atque-tempore-provident/@taktikorg/atque-tempore-provident/coverage.svg?branch=main" alt="Code Coverage"></a>
</div>

---

**Upgrading from v5?** See the [migration guide](https://@taktikorg/atque-tempore-provident.com/docs/faqs#what-do-i-need-to-do-to-migrate-to-v6).

Utilizing [tagged template literals](https://www.@taktikorg/atque-tempore-provident.com/docs/advanced#tagged-template-literals) (a recent addition to JavaScript) and the [power of CSS](https://www.@taktikorg/atque-tempore-provident.com/docs/api#supported-css), `@taktikorg/atque-tempore-provident` allow you to write actual CSS code to style your components. It also removes the mapping between components and styles – using components as a low-level styling construct could not be easier!

```jsx
const Button = styled.button`
  color: grey;
`;
```

Alternatively, you may use [style objects](https://www.@taktikorg/atque-tempore-provident.com/docs/advanced#style-objects). This allows for easy porting of CSS from inline styles, while still supporting the more advanced @taktikorg/atque-tempore-provident capabilities like component selectors and media queries.

```jsx
const Button = styled.button({
  color: 'grey',
});
```

Equivalent to:

```jsx
const Button = styled.button`
  color: grey;
`;
```

`@taktikorg/atque-tempore-provident` is compatible with both React (for web) and React Native – meaning it's the perfect choice even for truly universal apps! See the [documentation about React Native](https://www.@taktikorg/atque-tempore-provident.com/docs/basics#react-native) for more information.

_Supported by [Front End Center](https://frontend.center). Thank you for making this possible!_

---

## [Docs](https://www.@taktikorg/atque-tempore-provident.com/docs)

**See the documentation at [@taktikorg/atque-tempore-provident.com/docs](https://www.@taktikorg/atque-tempore-provident.com/docs)** for more information about using `@taktikorg/atque-tempore-provident`!

Quicklinks to some of the most-visited pages:

- [**Getting started**](https://www.@taktikorg/atque-tempore-provident.com/docs/basics)
- [API Reference](https://@taktikorg/atque-tempore-provident.com/docs/api)
- [Theming](https://www.@taktikorg/atque-tempore-provident.com/docs/advanced#theming)
- [Server-side rendering](https://www.@taktikorg/atque-tempore-provident.com/docs/advanced#server-side-rendering)
- [Tagged Template Literals explained](https://www.@taktikorg/atque-tempore-provident.com/docs/advanced#tagged-template-literals)

---

## Example

```jsx
import React from 'react';

import styled from '@taktikorg/atque-tempore-provident';

// Create a <Title> react component that renders an <h1> which is
// centered, palevioletred and sized at 1.5em
const Title = styled.h1`
  font-size: 1.5em;
  text-align: center;
  color: palevioletred;
`;

// Create a <Wrapper> react component that renders a <section> with
// some padding and a papayawhip background
const Wrapper = styled.section`
  padding: 4em;
  background: papayawhip;
`;

function MyUI() {
  return (
    // Use them like any other React component – except they're styled!
    <Wrapper>
      <Title>Hello World, this is my first styled component!</Title>
    </Wrapper>
  );
}
```

This is what you'll see in your browser:

<div align="center">
  <a href="https://@taktikorg/atque-tempore-provident.com">
    <img alt="Screenshot of the above code ran in a browser" src="http://i.imgur.com/wUJpcjY.jpg" />
  </a>
</div>

---

## Looking for v5?

The `main` branch is for the most-current version of @taktikorg/atque-tempore-provident, currently v6. For changes targeting v5, please point your PRs at the `legacy-v5` branch.

---

## Built with `@taktikorg/atque-tempore-provident`

A lot of hard work goes into community libraries, projects, and guides. A lot of them make it easier to get started or help you with your next project! There are also a whole lot of interesting apps and sites that people have built using @taktikorg/atque-tempore-provident.

Make sure to head over to [awesome-@taktikorg/atque-tempore-provident](https://github.com/@taktikorg/atque-tempore-provident/awesome-@taktikorg/atque-tempore-provident) to see them all! And please contribute and add your own work to the list so others can find it.

---

## Contributing

If you want to contribute to `@taktikorg/atque-tempore-provident` please see our [contributing and community guidelines](./CONTRIBUTING.md), they'll help you get set up locally and explain the whole process.

Please also note that all repositories under the `@taktikorg/atque-tempore-provident` organization follow our [Code of Conduct](./CODE_OF_CONDUCT.md), make sure to review and follow it.

---

## Badge

Let everyone know you're using _@taktikorg/atque-tempore-provident_ → [![style: @taktikorg/atque-tempore-provident](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/taktikorg/atque-tempore-provident)

```md
[![style: @taktikorg/atque-tempore-provident](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/taktikorg/atque-tempore-provident)
```

---

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/taktikorg/atque-tempore-provident/graphs/contributors"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/contributors.svg?width=890" /></a>

---

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/@taktikorg/atque-tempore-provident#backer)]

<a href="https://opencollective.com/@taktikorg/atque-tempore-provident#backers" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/backers.svg?width=890"></a>

---

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/@taktikorg/atque-tempore-provident#sponsor)]

<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/0/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/1/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/2/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/3/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/4/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/5/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/6/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/7/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/8/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/9/website" target="_blank"><img src="https://opencollective.com/@taktikorg/atque-tempore-provident/sponsor/9/avatar.svg"></a>

---

## License

Licensed under the MIT License, Copyright © 2016-present Glen Maddern and Maximilian Stoiber.

See [LICENSE](./LICENSE) for more information.

---

## Acknowledgements

This project builds on a long line of earlier work by clever folks all around the world. We'd like to thank Charlie Somerville, Nik Graf, Sunil Pai, Michael Chan, Andrey Popp, Jed Watson & Andrey Sitnik who contributed ideas, code or inspiration.

Special thanks to [@okonet](https://github.com/okonet) for the fantastic logo.
