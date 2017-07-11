You are going to build a photo gallery which will download a list of images from a server and display them in a dynamically resizing grid. You will be able to click on any image to enter a presentation mode, and view other images using "previous" and "next" buttons. You will also eventually implement an auto slideshow mode, where images will automatically change after a certain period of time.

To help you get started, you will need to structure your project into the following way for the assignments. Submission instructions are given in the end of this document.

- Root folder
    - css
        - (all stylesheets go in this folder)
    - js
        - (all JavaScript files go in this folder)
    - libs
        - (library files provided by us in this folder)
    - images
        - (all images go in this folder)
    - index.html
        - (this should be the entry point to your website)

For this particular assignment, you will write some basic HTML and CSS to build the homepage for the web app. There is no JavaScript required for this assignment, so you will be penalized if you use JavaScript for this assignment.

The file layout.png [TODO] provides a wireframe of what the user interface should look like. You are free to choose colours and fonts of your own choice.

**Tasks**

1. Create the HTML layout that will be required to generate the web page provided in the screenshot. Your homepage should include the following elements:
    - Div (id=mainBody)
        - Heading
        - Table (id=imagesGrid)
            - Row 1
                - Cell 1
                    - Image 1
                - Cell 2
                    - Image 2
                - Cell 3
                    - Image 3
                - Cell 4
                    - Image 4
                - Row 2
                    - ...

    - Notes:
        - You can find all 8 images here [TODO].
        - The images will likely be too big to fit on the screen, but that's OK, since that will be fixed in the next task.

2. Create a CSS stylesheet to add relevant styles that would help you design the layout for the web page. A few things to keep in mind:
