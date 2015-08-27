# flippingplugin
The JQuery plugin for my Flip-Book-Portfolio

If you are looking for a fun and interesting way to put together a memorable portfolio you have come to the right place. Included in this file are the bare bones HTML and CSS as well as a place to store your choice of images. Please use open source images or things that you own to make it unique. 
Also I have included the original code pen I-Pad Flip Book (germanflipbook.html) so that you can compare it to mine. I would like you to include this original in your files somewhere to help others along the way.
Now, let's disect this code.

First, the title found in the following example must remain "I-Pad Flip Book." Also, the second link tag holds the text choices. I used Google Fonts Aramarth. It was really simple to go on Google Fonts and copy and paste the link for the text of my choice into my HTML document. 
<!DOCTYPE html>
<html >
<head>
  <meta charset="UTF-8">
  <title>iPad Page Flip</title>
  <link href="css/style.css" rel="stylesheet">
  <link>
This next piece of code is very important it contains the div class, article class, and section class. Please DO NOT alter these or you will break the flip action of the book. 
<div class="scene">
    <article class="book">
      <section class="page active">
        <div class="front">
The page active section class is letting the "page" be responsive to your click. The div class notes where you are and helps keep track of each rotation from front to back.
Also, if you put links inside the book, they must be on the "back" page. 
The background was the trickist part. We used an open source background and lightened it, then we flipped it over.
I hope this information helps you and if you have any questions feel free to send an email to the address in my profile.
