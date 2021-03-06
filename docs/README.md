---
pageClass: home-page

name: Stanley Ang
profile: /img/profile.png

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/angsanley
  - title: linkedin
    icon: "/icons/linkedin.svg"
    link: https://www.linkedin.com/in/angsanley
  - title: instagram
    icon: "/icons/instagram.svg"
    link: https://www.instagram.com/angsanley
  - title: twitter
    icon: "/icons/twitter.svg"
    link: https://twitter.com/angsanley

bio: Mobile Application and Technology student at BINUS University
email: angsanley(at)icloud.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I'm a Computer Science student at [BINUS University](https://binus.ac.id/) currently studying Mobile Application and Technology.

I love everything tech-related, from designing UI/UX to creating real-world problem-solving apps.


## Projects


[→ Full list](/projects/)

<ProjectCard image="/img/adab.png" hideBorder=true>

  **Ayo Dengar Ayo Bicara**

  Andrew C., Brian R., Chandra
  
  Ayo Dengar Ayo Bicara (ADAB) is an app to help deaf and mute students at BINUS University by providing access to real-time speech transcription service allowing them to better understand the lecturers.
  
  [[Press](https://student.binus.ac.id/2020/09/aplikasi-adab-to-connect-dari-binusian-untuk-binusian/)] [[Docs](https://bearcatsdev.github.io/docs/adab/)] [[GitHub](https://github.com/bearcatsdev/adab)] [[Google Play Store](https://play.google.com/store/apps/details?id=com.ambinusian.adab)]

</ProjectCard>

<ProjectCard image="/img/rokaru.png" hideBorder=true>

**Rokaru**

Andrew C., Andrew M. T.

Rokaru is a mobile-based application that was created and designed specifically to help increase the level of public awareness of MSMEs in the surrounding environment.

[[GitHub](https://github.com/werdna521/rokaru)] [[YouTube](https://www.youtube.com/watch?v=qXvih-D7XDo)]

</ProjectCard>


## Awards & Honors

### Competitions

- 1st Champion of **BINUS Hackathon 2020**
- Top 8 finalists in **UMN BIOS Hackathon 2019**
- Finalist in **Compfest 11 Innovative App Competition by Tokopedia**
- Finalist in **UAJY Siloam Hackathon 2019**

### Awards

- Best Freshmen Leader in **BINUS FYP 2023**

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
