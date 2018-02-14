# Using Jing

(delete this and write your content here)

## Image syntax and tips

* Image syntax is **almost** the same as link syntax. The syntax is a leading exclamation point, followed by image *alt text* in [square brackets], then the image *file path* in (parentheses).

    For example:

    ```md
    ![My avatar](./path-to-avatar.png)
    ```

* All file paths in MkDocs are relative to the `docs/` directory, which means you use that as a starting point&mdash;not the project root. Your file paths will look like `./images/image.png`, NOT `./docs/images/image.png`.

* A blank line in Markdown indicates a new paragraph. If you have two consecutive lines with NO blank space in between, they will appear on the *same* line when rendered.

    For example:

    ```md
    This graphic is inline:
    ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)
    ```

    ...and

    ```md
    This graphic is inline: ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)
    ```
    ...both produce this:

    This graphic is inline:
    ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)

    Where *this* example...

    ```md
    This graphic is on its own line:

    ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)    
    ```

    ...produces this:

    This graphic is on its own line:

    ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)


## Sample Jing images

These images are from the Jing interface and are difficult (or impossible) to capture using Jing itself. I've provided them here to get you started. Use them however it seems appropriate in your documentation.

* Jing Sun (Collapsed)
    ![Jing Sun Collapsed](./images/jing-sun-collapsed.png)

* Jing Sun (Expanded)
    ![Jing Sun Expanded](./images/jing-sun-expanded.png)
