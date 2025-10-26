---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <p style="font-size: 0.8em;">  
        Ihcil@OUC
        </p>     
      image:
        filename: ihcil.jpg
      text: |
        <p style="font-size: 0.88em;">  <br>
        实验室描述（未编辑）
        </p>    

  # - block: collection
  #   content:
  #     title: 近期动态
  #     subtitle:
  #     text:
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: list
  #     columns: '1'  

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="团队成员 →" %}}
    design:
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       <div style="width: 30%; margin: 0 auto; overflow: hidden;">
  #         <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=QJLp3xQ-w7019B5p3jHJSpwxfsmjIoKGPvyGMIRtuXU&cl=ffffff&w=a"></script>
  #       </div>


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-4">
              <h5 class="text-muted" style="font-size: 0.95rem;">友情链接</h5>
              <ul class="list-unstyled" style="font-size: 0.9rem;">
                <li><a href="https://www.ai-ouc.cn/" target="_blank">中国海洋大学人工智能研究院</a></li>
                <li><a href="https://it.ouc.edu.cn/" target="_blank">中国海洋大学信息科学与工程学部</a></li>
              </ul>
            </div>
            <div class="col-md-4 text-center">
              <div style="margin-top: 1rem;">
                <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=QJLp3xQ-w7019B5p3jHJSpwxfsmjIoKGPvyGMIRtuXU&cl=ffffff&w=a"></script>
              </div>
            </div>
            <div class="col-md-4">
              <!-- 右侧部分为空 -->
            </div>
          </div>
        </div>
    design:
      columns: '1'
---
