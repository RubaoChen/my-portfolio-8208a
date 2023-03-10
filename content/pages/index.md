---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Welcome to my Portfolio Website
    subtitle: Data Analyst. Market researcher
    text: >
      Hi , I am Rubao Chen, an experienced data analyst and market researcher.
      This website showcases some of the data analysis projects I did using
      Python, SQL and Tableau.


      Please contact me if you want to work with me!
    actions: []
    media:
      type: ImageBlock
      url: /images/WechatIMG123.jpeg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-16
          - pb-16
          - pl-4
          - pr-11
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-e
    backgroundSize: full
    title: Tableau Dashboard
    subtitle: Visit @RubaoChen on Tableau Public
    actions:
      - type: Button
        label: VISIT ALL
        url: 'https://public.tableau.com/app/profile/rubao.chen'
        style: primary
        iconPosition: right
        icon: arrowRight
        showIcon: true
    backgroundImage:
      type: BackgroundImage
      url: /images/屏幕快照 2023-01-06 22.55.20-4b38ed9f.png
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 85
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-16
          - pb-96
          - pr-9
          - pl-20
        alignItems: flex-start
        justifyContent: center
        flexDirection: row
        borderRadius: none
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      type: ImageBlock
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: "Exploratory Data Analysis\_ (EDA)"
    actions:
      - type: Button
        label: CODE
        showIcon: true
        icon: arrowRight
        style: primary
        url: >-
          https://github.com/RubaoChen/Data-analysis-project-portfolio/blob/main/SQL_Explore%20International%20Debt%20Statistics/Explore%20International%20Debt%20Statistcis.ipynb
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/debt.jpeg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-11
          - pb-11
          - pl-10
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
        fontWeight: 500
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: >+
      This project explores and analyse global debt using the World Bank
      dataset.

    subtitle: SQL：select. group by. order by. where
  - type: HeroSection
    colors: colors-c
    elementId: ''
    backgroundSize: full
    title: Web Scraping & NPL
    subtitle: Python：BeautifulSoup. requests. nltk
    actions:
      - type: Button
        label: CODE
        showIcon: true
        icon: arrowRight
        style: primary
        url: >-
          https://github.com/RubaoChen/Data-analysis-project-portfolio/blob/main/Web%20Scraping%20%26%20NPL%20for%20Novel%20Word%20Frequency/Web%20Scraping%20%26%20NPL%20for%20Novel%20Word%20Frequency.ipynb
    media:
      type: ImageBlock
      url: /images/post-4.jpg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-11
          - pb-11
          - pl-10
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
        fontWeight: 500
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: >-
      This project will find out what are the most frequent words in Herman
      Melville's novel, Moby Dick, and how often do they occur?
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Customer Segmentation
    subtitle: 'Python: numpy. pandas. matplotlib. seaborn. sklearn'
    text: >
      This report processes and segment customer purchase data using a K-means
      clustering algorithm, including a snake plot and heatmap to visualize the
      resulting clusters and feature importance.
    actions:
      - type: Button
        label: CODE
        showIcon: true
        icon: arrowRight
        style: primary
        url: >-
          https://github.com/RubaoChen/Data-analysis-project-portfolio/blob/main/Customer%20Segmentation%20by%20k-mean%20Clustering/%20Customer%20Segmentation%20by%20k-mean%20Clustering.ipynb
    media:
      type: ImageBlock
      url: /images/k-mean clustering.png
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-11
          - pb-11
          - pl-10
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: HeroSection
    colors: colors-c
    elementId: ''
    backgroundSize: full
    title: A/B test
    subtitle: 'Python: numpy. pandas. matplotlib. seaborn'
    text: >
      This project try to analyse the retention rate for two different version
      of a mobile game with A/B test.
    actions:
      - type: Button
        label: CODE
        showIcon: true
        icon: arrowRight
        style: primary
        url: >-
          https://github.com/RubaoChen/Data-analysis-project-portfolio/blob/main/A:B%20test%20for%20mobile%20game%20retention/A:B%20test%20for%20mobile%20game%20retention%20.ipynb
    media:
      type: ImageBlock
      url: /images/Cookie Cats.png
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-11
          - pb-11
          - pl-10
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---
