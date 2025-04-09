---
title: Home
slug: /
sections:
  # Hero Section
  - type: GenericSection
    title:
      text: Hi, I'm Pahuldeep Singh Dhingra - Data Scientist|
      color: text-dark
      type: TitleBlock
    subtitle: MS in Data Science & Analytics | Aspiring Data Scientist
    text: >
      I’m a Graduate Teaching Assistant at Florida Atlantic University, pursuing an MS in Data Science and Analytics. 
      I’m passionate about leveraging data to uncover insights through machine learning, deep learning, and analytics. 
      My goal is to become a Data Scientist, AI/ML Engineer, or Data Analyst. Check out my projects below!
    actions:
      - label: View Projects
        altText: ''
        url: '#projects'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: Contact Me
        altText: ''
        url: '#contact'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
    media:
      url: /images/headshot.jpg
      altText: Headshot of Pahuldeep Singh Dhingra
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16

  # Divider for spacing
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
    
  # Skill Section
  - type: FeaturedItemsSection
    title:
      text: My Skills
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Tools and Technologies I Work With
    items:
      - type: FeaturedItem
        title: Python
        subtitle: Programming Language
        text: >-
          Experienced in using Python for data analysis, machine learning, and visualization with libraries like pandas, scikit-learn, and matplotlib.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Machine Learning
        subtitle: Model Development
        text: >-
          Skilled in building and evaluating machine learning models, including regression, classification, and clustering techniques.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Deep Learning & LLMs
        subtitle: Advanced AI
        text: >-
          Exploring deep learning frameworks like TensorFlow and PyTorch, with a focus on generative AI and large language models (LLMs).
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  
  # Divider for Spacing
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  
  # Projects Section
  - type: CarouselSection
    title:
      text: My Projects
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Data Science Projects I’ve Worked On
    items:
      - type: FeaturedItem
        title: Predicting House Prices with Machine Learning
        subtitle: Regression Model
        text: >-
          Built a regression model using Python and scikit-learn to predict house prices. 
          Performed data preprocessing, feature engineering, and achieved 85% accuracy. 
          Visualized results using matplotlib.
        image:
          url: /images/house-prices-viz.jpg
          altText: House prices visualization
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions:
          - label: View on GitHub
            url: https://github.com/pahuldeep/house-prices-project
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            type: Link
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        elementId: projects
      - type: FeaturedItem
        title: Customer Segmentation with Clustering
        subtitle: K-means Clustering
        text: >-
          Used K-means clustering to segment customers for a retail dataset. 
          Preprocessed data with pandas, applied clustering with scikit-learn, and visualized results using Tableau.
        image:
          url: /images/customer-segmentation.jpg
          altText: Customer segmentation visualization
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions:
          - label: View on GitHub
            url: https://github.com/pahuldeep/customer-segmentation
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            type: Link
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    elementId: projects
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center

  # Divider (optional, for spacing)
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection

  
  # Contact Section
  - type: GenericSection
    title:
      text: Contact Me
      color: text-dark
      type: TitleBlock
    subtitle: Let’s Connect
    text: |-
      I’d love to hear from you! Reach out via the form below, or connect with me on:
      - Email: pahuldeepsingh531@gmail.com
      - LinkedIn: [Pahuldeep Singh Dhingra](https://www.linkedin.com/in/pahuldeepsing/)
      - GitHub: [pahuldeep](https://github.com/pahul1712)
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    elementId: contact
    colors: bg-light-fg-dark
    type: GenericSection

seo:
  metaTitle: Pahuldeep Singh Dhingra | Data Science Portfolio
  metaDescription: Portfolio of Pahuldeep Singh Dhingra, an MS Data Science student at Florida Atlantic University, aspiring to be a Data Scientist or AI/ML Engineer.
  socialImage: /images/headshot.jpg
  type: Seo
type: PageLayout
---