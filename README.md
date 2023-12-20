
# <img width="25" src="https://raw.githubusercontent.com/sgkens/resources/main/modules/psparagraph/dist/v1/psparagraph-logo-x128.png"/>  **psparagraph**

<!--license-->
<a href="https://github.com/sgkens/psparagraph/">
  <img src="https://img.shields.io/github/license/sgkens/psparagraph"/>
</a> 
<!--Code-Factor-->
<a href="https://www.codefactor.io/repository/github/sgkens/psparagraph">
  <img src="https://www.codefactor.io/repository/github/sgkens/psparagraph/badge"/>
</a>
<!--coverage-->
<a href="https://coveralls.io/github/sgkens/psparagraph">
  <img src="https://img.shields.io/coverallsCoverage/github/sgkens/psparagraph?branch=main"/>
</a>

---

**psparagraph** is a function that generates readable text by indenting it, similating the effect of a paragraph.

|BUILD|RELEASES|
|-|-|
|<a href="https://ci.appveyor.com/project/sgkens/psparagraph"><img src="https://img.shields.io/appveyor/build/sgkens/psparagraph/main?logo=appveyor&label=appveyor"></a>|<a href="https://github.com/sgkens/psparagraph/releases"><img src="https://img.shields.io/github/v/tag/sgkens/psparagraph?logo=github&label=Latest%20Release%20Tag"></a>||<a href="https://gitlab.lab.davilion.online/powershell/commitfusion/-/pipelines"><img src="https://gitlab.lab.davilion.online/powershell/commitfusion/badges/main/pipeline.svg"></a>|

## 🟪 Cmdlets/Functions

#### 🔹**New-Paragraph**
New-Paragraph takes 3 parameters: `[in]position`, `[int]indent`, `[string]string`

```powershell
New-Paragraph -position 40 -indent 5 -string "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tincidunt elit ut eros eleifend rhoncus sit amet sit amet mauris. In vestibulum id neque vel blandit. Integer id mauris quis justo elementum condimentum eu eu odio. Mauris mollis a odio a fermentum. Maecenas auctor iaculis elementum. Sed cursus, erat sed faucibus dignissim, quam dolor viverra mi, ac pellentesque magna quam quis metus. In neque justo, pulvinar vitae vehicula eget, euismod non diam. In auctor enim vitae lectus mollis condimentum. In vitae sapien molestie, condimentum dui non, placerat sapien. Nullam eget dapibus nibh, ac mollis elit. Suspendisse venenatis sit amet mi non gravida. "
```

## Ouput indent `5`

<pre>
     Lorem ipsum dolor sit amet, consectetur
     adipiscing elit. Vivamus tincidunt elit
     ut eros eleifend rhoncus sit amet sit
     amet mauris. In vestibulum id neque vel
     blandit. Integer id mauris quis justo
     elementum condimentum eu eu odio. Mauris
     mollis a odio a fermentum. Maecenas
     auctor iaculis elementum. Sed cursus,
     erat sed faucibus dignissim, quam dolor
     viverra mi, ac pellentesque magna quam
     quis metus. In neque justo, pulvinar
     vitae vehicula eget, euismod non diam.
     In auctor enim vitae lectus mollis
     condimentum. In vitae sapien molestie,
     condimentum dui non, placerat sapien.
     Nullam eget dapibus nibh, ac mollis
     elit. Suspendisse venenatis sit amet mi
     non gravida.
</pre>

## Ouput indent `10` and position `80`

<pre>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tincidunt elit
          ut eros eleifend rhoncus sit amet sit amet mauris. In vestibulum id neque vel
          blandit. Integer id mauris quis justo elementum condimentum eu eu odio. Mauris
          mollis a odio a fermentum. Maecenas auctor iaculis elementum. Sed cursus, erat
          sed faucibus dignissim, quam dolor viverra mi, ac pellentesque magna quam quis
          metus. In neque justo, pulvinar vitae vehicula eget, euismod non diam. In auctor
          enim vitae lectus mollis condimentum. In vitae sapien molestie, condimentum dui
          non, placerat sapien. Nullam eget dapibus nibh, ac mollis elit. Suspendisse
          venenatis sit amet mi non gravida.
</pre>
