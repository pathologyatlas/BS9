







```
r language BS9, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis Giardiasis, Duodenum , echo = (language == "TR")
## BS9 - Giardiasis, Duodenum {#sec-BS9 }
```


```
asis Giardiasis, Duodenum , echo = (language == "EN")
## BS9 - Giardiasis, Duodenum {#sec-BS9 }
```






```
r BS9 screenshot HE1, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS9-HE1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS9/HE1.html",
  file = "./screenshots/BS9-HE1_screenshot.png"
)
}
```






```
r BS9 screenshot HE2, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS9-HE2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS9/HE2.html",
  file = "./screenshots/BS9-HE2_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**Giardiasis, Duodenum**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS9-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS9/HE1.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS9/HE1.html)
```

```
asis, echo = (language == "EN")

**Giardiasis, Duodenum**

[![Click for Full Screen WSI](./screenshots/BS9-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS9/HE1.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS9/HE1.html)

```






```
asis, echo = (language == "TR")

**Giardiasis, Duodenum**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS9-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS9/HE2.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS9/HE2.html)
```

```
asis, echo = (language == "EN")

**Giardiasis, Duodenum**

[![Click for Full Screen WSI](./screenshots/BS9-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS9/HE2.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS9/HE2.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS9/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS9/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```







```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS9/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS9/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

Giardiasis, Duodenum

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

Giardiasis, Duodenum

:::

```









:::::











