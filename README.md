
![Build Status](https://gitlab.com/kshlug/kshlug.gitlab.io/badges/master/build.svg)


<div dir="rtl">
---


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*


- [چگونه میتوانید کمک کنید؟](#%DA%86%DA%AF%D9%88%D9%86%D9%87-%D9%85%DB%8C%D8%AA%D9%88%D8%A7%D9%86%DB%8C%D8%AF-%DA%A9%D9%85%DA%A9-%DA%A9%D9%86%DB%8C%D8%AF%D8%9F)
    - [نحوه ی کار با پروژه بر روی کامپیوتر شخصی](#%D9%86%D8%AD%D9%88%D9%87-%DB%8C-%DA%A9%D8%A7%D8%B1-%D8%A8%D8%A7-%D9%BE%D8%B1%D9%88%DA%98%D9%87-%D8%A8%D8%B1-%D8%B1%D9%88%DB%8C-%DA%A9%D8%A7%D9%85%D9%BE%DB%8C%D9%88%D8%AA%D8%B1-%D8%B4%D8%AE%D8%B5%DB%8C)
        - [پیش نمایش وبسایت](#%D9%BE%DB%8C%D8%B4-%D9%86%D9%85%D8%A7%DB%8C%D8%B4-%D9%88%D8%A8%D8%B3%D8%A7%DB%8C%D8%AA)
    - [Troubleshooting](#troubleshooting)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# چگونه میتوانید کمک کنید؟

## نحوه ی کار با پروژه بر روی کامپیوتر شخصی
</div>
To work locally with this project, you'll have to follow the steps below:

1. **Fork**, clone or download this project
1. [Install][] **Hugo**
1. Preview your project: `hugo server`
1. Add content
1. Generate the website: `hugo` (غیر لازم برای این پروژه)

<div dir="rtl">
برای مطالعه ی بیشتر برای کار با هوگو به وبسایت آن مراجعه کنید.

### پیش نمایش وبسایت
</div>


If you **clone** or **download** this project to your local computer and run `hugo server`,
your site can be accessed under `localhost:1313/hugo/`.




<div dir="rtl">
    
### ارسال مطلب و ویرایش وبسایت


برای این کار کافیست تغییرات را به این مخزن push کنید.
این مخزن توسط travis ci بویلد میشود و دیتای سایت در این
[مخزن][] قرار میگیرد
شما نیاز نیست کار خاصی کنید!
</div>


## Troubleshooting

1. CSS is missing! That means two things:

    Either that you have wrongly set up the CSS URL in your templates, or
    your static generator has a configuration option that needs to be explicitly
    set in order to serve static assets under a relative URL.


[ci]: https://about.gitlab.com/gitlab-ci/
[hugo]: https://gohugo.io
[install]: https://gohugo.io/overview/installing/
[documentation]: https://gohugo.io/overview/introduction/
[userpages]: http://doc.gitlab.com/ee/pages/README.html#user-or-group-pages
[projpages]: http://doc.gitlab.com/ee/pages/README.html#project-pages
[post]: https://about.gitlab.com/2016/04/07/gitlab-pages-setup/#custom-domains
[مخزن]: http://github.com/kshlug/kshlug.github.io
