# Creating a Theme

Creating a theme is the first step in theme development.
<!-- Still trying to think of more details to add to a preface here -->

## Prerequisites

Themes are created using the Liferay Theme Generator. If you have not already done so, then you must install it with this command:

```bash
npm install -g generator-liferay-theme@10.x.x
```

Install the Yeoman and Gulp dependencies with this command:

```bash
npm install -g yo gulp
```

## Running the Liferay Theme Generator

Run the Liferay Theme Generator with these steps:

1. Run the Liferay Theme Generator using Yeoman:

    ```bash
    yo liferay-theme
    ```

    ```important::
       You can add the name of a base theme to this command to base your new theme off of it. For example, running ``yo liferay-theme:classic`` will base your new theme off of DXP's Classic theme.
    ```
    <!-- Add link to an explanation of changing the base theme. Maybe add a bit more explanation here too? Or even change the command to recommend starting with classic? -->

1. Type a name for your theme at the prompt. Press Enter to use the default, "My Liferay Theme".

    [Screenshot]

1. Type an ID for your theme at the prompt. When the theme is generated, the ID will determine the name of the folder that your theme is built inside of. You can also press Enter to use a default ID based on the name.

1. Use the arrow keys to select the version of Liferay DXP to build the theme for at the prompt. 

    [Screenshot]

1. Answer whether you would like to add Font Awesome as an available font for your theme.

1. After the theme has been generated, complete the process by using the arrow keys to select the appropriate deployment type for your theme. You can choose to deploy with a local app server, Docker container, or other address.

    [Screenshot]

1. Provide the location of the app server at the prompt, depending on which deployment type you are using.

    You may provide the app server directory, the Docker container name, or the host URL to locate the app server.

The theme is then generated and placed inside of a folder named after the ID you have chosen.

## Additional Information

[Changing Your Site's Appearance](../../../../getting-started/changing-your-sites-appearance.md)