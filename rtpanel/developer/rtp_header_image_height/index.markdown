---
title: rtp_header_image_height
---

### Description


Modifies the height of the header image under Appearance-> Header. Default is 190.


### Example



    
    function custom_rtp_header_image_height( $height ) {
    return 100;
    }
    add_filter( 'rtp_header_image_height', 'custom_rtp_header_image_height' );
