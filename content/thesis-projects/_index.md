---
title: Thesis Projects
type: landing

sections:
  - block: portfolio
    id: studentprojects
    content:
      title: Thesis Projects
      subtitle: Topics
      text: >-
        These thesis projects can be started at any time (including holidays) and can span over semester boundaries.
        Remark: We are open to new proposals in our research fields---if you are interested, feel free to contact us!
        <br><br>
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - thesis-projects
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Systematic Literature Review
          tag: Systematic Literature Review
        - name: Data Analysis
          tag: Data Analysis
        - name: Recommender Systems
          tag: Recommender Systems
        - name: User Study
          tag: User Study
        - name: Qualitative Research Methods
          tag: Qualitative Research Methods
        - name: Experimental Study
          tag: Experimental Study
    design:
      view: masonry
      columns: '1'
      flip_alt_rows: false
  - block: markdown
    content:
      title: Systematic Literature Review topics
      subtitle: (for Bachelor thesis projects)
      text: >-
        What about doing a [Systematic Literature Review, according to Kitchenham](https://www.elsevier.com/__data/promis_misc/525444systematicreviewsguide.pdf)?
        With such an approach, you would have to deal systematically with literature---and keep it well organized. It requires finding literature, documenting the process, labeling publications according to a prepared set of criteria, extracting some content from the papers (again in a labeled way), and probably aggregating labels to have a coherent picture. Then you could "quantify" the labels à la: X\% of papers deal with subtopic A, Y\% deal with subtopic B, Z\% deal with both topics, etc. To get an impression of what such work looks like, here are examples of systematic literature reviews that we have done:<br><br>
        {{< cite page="bauer-2024-values" view="1" >}}
        {{< cite page="bauer-2024-landscape" view="1" >}}
    design:
      columns: '1'
---
