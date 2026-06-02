---
# Leave the homepage pretty much standard
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        I am a third-year PhD candidate in Economics at Stockholm University, and
        currently visiting Columbia Business School, hosted by Stephen Zeldes.
        My research spans **household finance** and **public economics**.
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Working Papers
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: '1'
---
