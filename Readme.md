Attachments 2 for Cotonti
=========================

With this plugin you can attach files and images to any Cotonti objects including pages, forum posts and organize them into galleries or downloads.

Author: [Vladimir Sibirov](https://github.com/trustmaster) ([Trustmaster](https://www.cotonti.com/users/Trustmaster))

Plugin page and documentstion: https://www.cotonti.com/en/extensions/files-media/attach2

Forum discussion: https://www.cotonti.com/forums?m=posts&q=9217 (Russian)

## Thanks

Thanks to them work you could use that good plugin again 
[Pavlo Tkachenko](https://github.com/Dayver) ([Dayver](https://www.cotonti.com/users/Dayver)),
[Kabak](https://github.com/Kabak) ([Kabak](https://www.cotonti.com/users/Kabak))


## Usage at forum
```php
// Attach to forum post
{FORUMS_POSTS_ROW_ID|att_widget('forums',$this,'attach2.link')}

// Displat at forum
{FORUMS_POSTS_ROW_ID|att_display('forums',$this)}   //  All by attach list queue
{FORUMS_POSTS_ROW_ID|att_gallery('forums',$this)}   //  gallery
{FORUMS_POSTS_ROW_ID|att_downloads('forums',$this)} //  for downloading not picture

// 1000*600 picture<p>&lt; img src="{FORUMS_POSTS_ROW_ID|att_get('forums',$this)|att_thumb($this,1000,600,height)}" alt="{FORUMS_POSTS_ROW_ID|att_get('posts',$this,'title')}" class="img-fluid"/&gt;</p>
```

## Usage at Pages
```php
// Attach to page
{PAGE_ID|att_widget('page',$this,'attach2.link')}

// Display at page 
{PAGE_ID|att_display('page',$this)}   //  All by attach list queue
{PAGE_ID|att_gallery('page',$this)}   //  gallery
{PAGE_ID|att_downloads('page',$this)} //  for downloading not picture
```

## Usage at Comments
```php
// Attach to comment
{COMMENTS_ROW_ID|att_widget('comments',$this,'attach2.link')} 

// Display at Comment
{COMMENTS_ROW_ID|att_display('comments',$this)}     //  All by attach list queue
{COMMENTS_ROW_ID|att_gallery('comments',$this)}     //  gallery
{COMMENTS_ROW_ID|att_downloads('comments',$this)}   //  for downloading not picture
```
