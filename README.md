# How to Add a New Article

Follow these simple steps to add a new article using the Jupyter Notebook named `new_article`.

## Step 1: Open the Jupyter Notebook

1. Launch Jupyter Notebook on your computer.
2. Open the `new_article` notebook.

## Step 2: Set the Article ID

1. Before running the cell, ensure that the `article_id` variable is set correctly with a unique identifier (USE ONLY LOWERCASE ALPHABETS AND UNDERSCORES!!).

## Step 3: Run the Notebook

1. Executing the notebook will create a new folder for your article using the `article_id` you set in Step 2.

## Step 4: Prepare Your Article Information

Locate your new folder in the `articles` directory and open the `info.json` file in the newly created article folder. You will need to fill out the following fields:

- **title**: The title of your article (Donot use ":").
- **author_id**: Your unique author ID.
- **display**: Set to `true` if you want the article to be displayed.
- **date**: Enter the date in MM-DD-YYYY format.
- **category**: Specify whether it is "News" or "Research".
- **tags**: List relevant tags (e.g., "tag1", "tag2").
- **platforms**: Choose the platforms where you want to display your article (e.g., "tardis", "kg", "dti"). Leaving this empty would mean your article won't be visible on any of the websites.
- **short_description**: Write a brief summary of your content (Donot use ":").
- **cover_image_height**: Set the height of your cover image (e.g., "520px").
- **cover_image_width**: Set the width of your cover image (e.g., "330px").
- **cover_image**: Provide the path to your cover image (e.g., "media/images/your_image_name.extension").
- **content**: Fill in the content sections (1_para, 2_img, 3_para, 4_vid) as needed. The number in front of the key defines the order in which the content will be shown on the article.
- **people_involved_ids**: List IDs of collaborators involved in the article.
- **links**: Add any relevant links (if applicable).
- **twitter**: Specify if there is any Twitter handle related to the article (if applicable).

## Step 5: Add Media Files

1. If you have images or videos, place them in the `media/images` directory of your new article folder.
2. Make sure that the paths in the `info.json` file correspond to the media files you added.

## Step 6: Verify Your Article

1. Double-check all entries in the `info.json` file to ensure accuracy.
2. Make sure the media files are correctly placed and referenced.

## Step 7: Open a PR

1. Once everything is verified, you can proceed to open a PR.
