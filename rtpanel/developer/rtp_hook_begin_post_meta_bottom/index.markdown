---
title: rtp_hook_begin_post_meta_bottom
---

### Description


Adds content before Bottom Post Meta Box. Depends on the default applied rtp_hook_post_meta_bottom hook.


### Example



    
    function custom_hook_begin_post_meta_bottom() { ?>
    <p>This is before Bottom Post Meta Box</p><?php
    }
    add_action( 'rtp_hook_begin_post_meta_bottom', 'custom_hook_begin_post_meta_bottom' );
