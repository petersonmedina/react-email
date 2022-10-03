![React Email img cover](https://react-email-assets.vercel.app/img.png)

<div align="center"><strong>@react-email/avatar</strong></div>
<div align="center">Display an simple avatar or an avatar with invitation in your email.</div>
<br />
<div align="center">
<a href="https://react.email">Website</a> 
<span> · </span>
<a href="https://github.com/zenorocha/react-email">GitHub</a> 
<span> · </span>
<a href="https://react.email/discord">Discord</a>
</div>

## Install

Install component from your command line.

#### With yarn

```sh
yarn add @react-email/avatar -E
```

#### With npm

```sh
npm install @react-email/avatar -E
```

## Getting started

Add the component to your email template. Include styles where needed.

Simple Avatar

```jsx
import { Avatar } from '@react-email/avatar';

const Email = () => {
  return <Avatar from="cat.jpg" fromAlt="Cat" />;
};
```

Avatar with invitation

```jsx
const Email = () => {
  return <Avatar from="cat.jpg" fromAlt="Cat" to="dog.jpg" toAlt="Dog" />;
};
```

## Props

| Name    | Type   | Default | Description                        |
| ------- | ------ | ------- | ---------------------------------- |
| from    | string |         | The path to the image From         |
| fromAlt | string |         | Alternate description for an image |
| to      | string |         | The path to the image To           |
| toAlt   | string |         | Alternate description for an image |

## Support

This component was tested using the most popular email clients.

| <img src="https://react.email/static/images/gmail.svg" width="48px" height="48px" alt="Gmail logo"> | <img src="https://react.email/static/images/apple-mail.svg" width="48px" height="48px" alt="Apple Mail"> | <img src="https://react.email/static/images/outlook.svg" width="48px" height="48px" alt="Outlook logo"> | <img src="https://react.email/static/images/yahoo-mail.svg" width="48px" height="48px" alt="Yahoo! Mail logo"> | <img src="https://react.email/static/images/hey.svg" width="48px" height="48px" alt="HEY logo"> | <img src="https://react.email/static/images/superhuman.svg" width="48px" height="48px" alt="Superhuman logo"> |
| --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Gmail ✔                                                                                             | Apple Mail ✔                                                                                             | Outlook ✔                                                                                               | Yahoo! Mail ✔                                                                                                  | HEY ✔                                                                                           | Superhuman ✔                                                                                                  |

## License

MIT License

```

```