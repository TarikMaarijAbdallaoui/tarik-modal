# Tarik Modal

Tarik Modal is a lightweight and customizable JavaScript library for displaying modal messages in your web applications. With Tarik Modal, you can easily create and manage modal dialogs to provide users with important information or prompt them for input in a clean and user-friendly way.

### Features

- Create and display modal dialogs with ease.


### Installation

You can install **Tarik Modal** using npm:

```zsh
npm install tarik-modal
```

### Usage

To use **Tarik Modal**, follow these simple steps:

1. Import the Modal from the `tarik-modal` library.
```javascript
import Modal from "tarik-modal";
```

2. Use the Modal Component in the JSX code block.
```javascript
const App = () => {
        const [open, setOpen] = useState(false)
        return <Modal fn={setOpen} open={open}>User created successfully!!</Modal>
};
```

### License

**Tarik Modal** is released under the MIT License. See the LICENSE file for more details.

### Feedback and Contributions

If you have any feedback, suggestions, or would like to contribute to **Tarik Modal**, please feel free to open an issue or create a pull request on the GitHub repository.

Enjoy using **Tarik Modal** in your web applications!