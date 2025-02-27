---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: "Here’s an updated and polished **Markdown content** for your website, reflecting that you’ve completed your B.Tech and are currently working in a company. This version is professional, concise, and suitable for showcasing on your personal website or portfolio.---# **Pramod Kumar Maurya**\_\__B.Tech in Information Technology | Data Science Enthusiast | Tech Professional_\_\_---\U0001F64F **Hello!**I’m **Pramod Kumar Maurya**, a passionate **tech professional** with a **B.Tech in Information Technology** from **Shri Ramswaroop Memorial College of Engineering & Management, Lucknow (UP)**. I recently graduated and am currently working as a **[Your Job Title]** at **[Your Company Name]**. My journey in technology has been driven by an insatiable curiosity and a commitment to continuous learning.---## **Education**- **B.Tech in Information Technology**\_\_\_ Shri Ramswaroop Memorial College of Engineering & Management, Lucknow (UP) *(20XX - 20XX)*\_\_\_ - Graduated with a strong foundation in software development, data science, and IT systems.\_\_- **B.Sc and M.Sc in Physics**\_\_\_ - Developed analytical and problem-solving skills through rigorous academic training.\_\_- **B.Ed in Physics & Maths**\_\_\_ - Reinforced my belief in the power of holistic education and lifelong learning.---## **Professional Experience**### **[Your Job Title]**\_\_**[Your Company Name]** – *[Location]*\_\_*(Month YYYY - Present)*\_\_- [Briefly describe your role and responsibilities. For example: \"Developing scalable solutions using Python and Flask, analyzing data with Power BI, and optimizing workflows.\"]*\_\_- [Highlight key achievements. For example: \"Automated reporting processes, reducing manual effort by 40%.\"]*\_\_- [Mention tools/technologies used. For example: \"Proficient in PostgreSQL, Microsoft Power BI, and cloud-based platforms.\"]*---## **Technical Skills**### **Programming Languages**- Python, SQL, JavaScript\_\_### **Data Science & Analytics**- Microsoft Power BI, Flask, Pandas, NumPy\_\_### **Databases**- PostgreSQL, MySQL\_\_### **Other Tools**- Git, MS Office Suite, REST APIs\_\_---## **Certifications**- **Data Science Training**\_\_\_ Completed a comprehensive training program with **Intenshala Training**, focusing on data visualization, analysis, and machine learning fundamentals.\_\_- **Teaching Certifications**\_\_\_ - CTET (Central Teacher Eligibility Test) – Both Papers\_\_\_ - STET (State Teacher Eligibility Test)\_\_- **Short Technical Courses**\_\_\_ - CCC (Course on Computer Concepts)\_\_\_ - PMKVY (Pradhan Mantri Kaushal Vikas Yojana) – Customer Service Training\_\_---## **My Journey in Data Science**My passion for **data science** was ignited during my training with **Intenshala**, where I gained hands-on experience in **data visualization**, **statistical analysis**, and **problem-solving** using tools like **Power BI** and **Flask**. I’m now applying these skills in real-world projects to drive innovation and efficiency.---## **My Philosophy**I believe in the power of **continuous learning** and **adaptability** in the ever-evolving tech landscape. As a professional, I strive to leverage technology to solve complex problems and create meaningful impact. Time should never be a barrier to pursuing one’s dreams, and I’m committed to pushing boundaries in my career.---## **What I’m Focused On**Currently, I’m focused on:\_\_- Developing scalable solutions using **Python**, **Flask**, and **PostgreSQL**.\_\_- Leveraging **data-driven insights** to optimize workflows and improve decision-making.\_\_- Staying updated with emerging technologies and contributing to innovative projects."
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
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
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
