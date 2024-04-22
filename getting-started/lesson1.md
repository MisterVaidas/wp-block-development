# Overview of the Gutenberg Block Editor

## Introduction to Gutenberg:

The block editor, also known as Gutenberg, replaces the traditional TinyMCE editor in WordPress. Despite its ongoing development, it's sufficiently mature to serve as the default editor in new WordPress installations.

## Functionality:

Gutenberg structures content into units called "blocks," each designed to hold specific types of content such as paragraphs, headings, or images. Users familiar with Gutenberg may know blocks like the Cover block, the Quote block, or the Gallery block.

## Development with Gutenberg:

Gutenberg blocks are developed using React. Custom blocks are implemented within WordPress plugins. The focus in this course is primarily on JavaScript and React rather than PHP. Participants will learn to create complex blocks that group multiple primitive blocks and style them as "newspaper columns."

## Technical Details:

Content is stored in the `wp_posts` table, as with the older TinyMCE editor. Gutenberg distinguishes itself by embedding HTML comments within the content to demarcate and provide metadata for each block, facilitating its rendering in browsers.