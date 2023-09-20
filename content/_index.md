---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:

  - block: markdown
    content:
      title: <p style="color:#000000; font-size:40pt"><b>JC STEM Lab of Smart City</b></p>
      subtitle:
      text: |
        <p style="color:#000000; font-size:20pt">
        <b>The JC STEM Lab of Smart City was founded by <a href="https://www.cs.cityu.edu.hk/~yugufang/">Prof. FANG Yuguang</a> in 2022 in Hong Kong, Our mission is to leverage vehicles to build a smarter city.</b>  
        </p> 
    design:
      columns: '1'
      background:
        image:
          filename: group2.jpg
          filters:
            brightness: 1
          parallax: True
          position: center
          size: contain
        text_color_light: False
        
          
      css_class: fullscreen
      spacing:
        padding: ['40px', '0', '20px', '0']
  # - block: hero
  #   content: 
  #     title: 
  #       JC STEM Lab of Smart City
  #     image:
  #       filename: group_photo.jpg
  #     text: | 
  #       <br>
  #       <p>
  #       The JC STEM Lab of Smart City was founded by <a href="https://www.cs.cityu.edu.hk/~yugufang/">Prof. FANG Yuguang</a> in 2022 in Hong Kong, Our mission is to leverage vehicles to build a smarter city.  
  #       </p>
        
  #   design:
  #     background:
  #       gradient_start: '#0476D0'
  #       gradient_end: '#D26085'
  #       text_color_light: true
  #       gradient_angle: 45

  - block: features
    design:
      background:
        color: 
    content:
      title: Our Research
      
      items:
        - name: Internet of Things
          description: The Internet of Things (IoT) is a network of interconnected devices that communicate and exchange data, enhancing automation and real-time monitoring in various fields, from home appliances to industrial machinery.
          icon: iot
          icon_pack: custom
        - name: Federated Learning
          description: Federated Learning is a machine learning approach where models are trained across multiple decentralized devices or servers holding local data samples, protecting privacy while still enabling collaborative learning.
          icon: chart-line
          icon_pack: fas
        - name: Smart City
          description: Our mission is to leverage vehicles to build a smarter city in Hong Kong
          icon: 🌆
          icon_pack: emoji
        - name: Wireless Communication
          description: Wireless communication refers to data transmission between devices without physical connections, using radio waves, infrared signals, or other electromagnetic waves.
          icon: 📱
          icon_pack: emoji
        - name: Vehicle as a Service (VaaS)
          description: We are delicated to use of vehicles to build a cost-effective service network, called the Vehicle as a Service (VaaS) paradigm.
          icon: car
          icon_pack: custom
        - name: Security & Privacy
          description: 
          icon: user-secret
          icon_pack: fas
        - name: Health Monitoring
          description: 
          icon: 🏥
          icon_pack: emoji
        - name: Semantic + AI Communications
          description: 
          icon: key
          icon_pack: fas 
        - name: Collaborative Distributed ML
          description: 
          icon: 🤝
          icon_pack: emoji
    
        
  - block: markdown
    content:
      title: Latest News
      subtitle: 
      text: |-

            
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Scrollable Content</title>
                <style>
                    .scrollable-content {
                        height: 800px;
                        overflow-y: scroll;
                        # border: 1px solid #ccc;
                        padding: 10px;
                    }
                </style>
            </head>
            <body>

            <div class="scrollable-content">
                <b>[01/18/2023]</b> 🔥🔥🔥 Congratulations to <b>Prof. Fang</b>, who has been elevated to <b><span style="color:#1565C0;"><a href="https://www.acm.org/media-center/2023/january/fellows-2022">  ACM Fellow</a>   </span></b>!!!
              <br> <br>
              <b>[08/05/2022]</b> 🔥🔥🔥 Congratulations to <b>Prof. Fang</b>, who will join the Department of Computer Science, City University of Hong Kong (CityU), as the <b>Chair Professor of Internet of Things</b>!!! 
              <br> <br>
              <b>[06/21/2022]</b> Congratulations to <b>Dr. Jianqing Liu</b>, our former member, who will join the Department of Computer Science, North Carolina State University (NC State), as an <b>assistant professor</b>!!! (6/21/2022) <br><br>
              <b>[05/10/2022]</b> Congratulations to <b>Kaichen</b>, who has accepted an <b>assistant professor</b> position in the Department of Electrical and Computer Engineering at <b>Michigan Technological University</b>!!! <br><br>
              <b>[05/05/2022]</b> Congratulations to <b>Linke</b>, our former member, who has been promoted to <b>Associate Professor</b> with tenure in the Department of Electrical and Computer Engineering at Clemson University!!!<br> <br>
              <b>[03/29/2022]</b> Congratulations to <b>Xianhao</b>, who has accepted a <b>tenure-track Assistant Professor</b> position in the Department of Electrical and Electronic Engineering at <b>The University of Hong Kong</b>!!! <br> <br>

              <b>[04/30/2022]</b> Congratulations to <b>Rui Hu</b> (a PhD student of Dr. Yanmin Gong), who has accepted an <b>Assistant Professor</b> position at the Department of Computer Science and Engineering, <b>University of Nevada, Reno</b>!!!  <br> <br>
              <b>[04/25/2022]</b> Congratulations to <b>Yifang Guo</b> and <b>Tianxi Ji</b> (PhD students of Dr. Pan Li), who have accepted <b>tenure-track</b> <b>Assistant Professor</b> positions in the Department of Computer and Information Sciences at <b>Towson University</b> and the Department of Computer Science at <b>Texas Technological University</b>, respectively!!! Congratulations to Pan as well!<br> <br>
              <b>[04/01/2022]</b> Congratulations to <b>Yaodan</b>, who has accepted an <b>assistant professor</b> position in the Department of Electrical and Computer Engineering at <b>Idaho State University</b>!!!<br> <br> 
              <b>[02/02/2022]</b> Congratulations to <b>Yanmin</b> and <b>Yuanxiong</b>, our former members, who have been promoted to <b>Associate Professor</b> with tenure at University of Texas at San Antonio!!! <br> <br>
              <b>[11/11/2022]</b> Congratulations to <b>Haichuan Ding</b>, who has joined the School of Cyberspace Science and Technology, <b>Beijing Institute of Technology<b>, Beijing, China, as a <b>full professor<b>! <br> <br>
            </div>

            </body>
            </html>
    design:
      columns: '2'
      background:
        image: 
          filename: 
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      # spacing:
      #   padding: ['20px', '0', '20px', '0']
      # css_class: fullscreen
      
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle: 
  #     text: 
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: event
  #   design:
  #     view: showcase
  #     columns: '2'
  
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
  #     background:
  #       image:
  #         filename: group_photo.jpg
  #     css_class: fullscreen
---