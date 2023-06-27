# Pastebin Plugin

The Pastebin Plugin is a plugin for the OpenAI GPT-3 model that extracts code examples from the model's response and saves them to pastebin.com.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/pastebin-plugin.git
    ```

2. Install the dependencies
    ```shell
    pip install -r requirements.txt
    ```

## Usage

1. Import the plugin in your code

    ```python
    import openai_plugin
import pastebin
import re

# Add the plugin code here
```

2. Create an instance of 'PastebinPlugin' class:

    ```python
plugin = PastebinPlugin()
```

3. Register the plugin:
    ```python
openai_plugin.register_plugin(plugin)
```

4. Run the plugin locally:
    ```python
    if __name__ == "__main__":
    openai_plugin.run_local()
    ```

## Configuration
Before running the plugin, make sure to update the pastebin_dev_key variable in the submit_to_pastebin method of the PastebinPlugin class with your actual Pastebin developer key.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


