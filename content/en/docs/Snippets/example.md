```yml
readfile:
    template: hugo_shortcode_named_args
    inline: false
    definitions:
      shortcode_name: readfile
      named_args:
        - source_key: file
          editor_key: file
          type: url
        - source_key: code
          editor_key: code
          optional: true
          remove_empty: true
          type: boolean
        - source_key: lang
          editor_key: lang
          optional: true
          remove_empty: true
          type: string
    preview:
      text: Read File
      subtext:
        - Display another file's contents
      icon: search
      gallery: 
        image: /preview-images/readfile.png
        text: Import the contents of an external file into a document
      view: gallery
    picker_preview:
      text: Read File
      subtext: Import the contents of an external file into a document
      icon: dashboard
      gallery: 
        image: /preview-images/readfile.png
        text: Import the contents of an external file into a document
    _inputs:
      file:
        type: url
```