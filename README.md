<<<<<<< HEAD
# codenula-embed-react-v2
=======
<!-- markdownlint-disable MD030 -->

# codenula Embed React

React library to display codenula chatbot on your website

![codenula](https://github.com/FlowiseAI/FlowiseChatEmbed/blob/main/images/ChatEmbed.gif?raw=true)

## Install

```bash
npm install codenula-embed-v2 codenula-embed-react-v2
```

or

```bash
yarn add codenula-embed-v2 codenula-embed-react-v2
```

## Import

Full Page Chat

```tsx
import { FullPageChat } from "codenula-embed-react-v2";

const App = () => {
  return (
    <FullPageChat
      chatflowid="your-chatflow-id"
      apiHost="http://localhost:3000"
    />
  );
};
```

Popup Chat

```tsx
import { BubbleChat } from "codenula-embed-react-v2";

const App = () => {
  return (
    <BubbleChat chatflowid="your-chatflow-id" apiHost="http://localhost:3000" />
  );
};
```
>>>>>>> upstream/main
