---
title: "Samples"
description: "See what's possible with Blowfish."
menu: "main"

cascade:
  showEdit: false
  showSummary: false
  hideFeatureImage: true
---

{{< lead >}}
Blowfish brings your content to life. :heart_eyes:
{{< /lead >}}

This section contains some demo pages that show how Blowfish renders different types of content. You can also see an example [taxonomy listing]({{< ref "tags" >}}) page.

_**Sidenote:** This page is just a standard Blowfish article listing and Hugo has been configured to `generate` a `samples` content type and display article summaries._

>cool stuff 
>--- Cédrick BELER

{{< lead >}}
Introduction : Une ceinture verte est un réseau d'espaces naturels ou agricoles protégés qui ceinturent un territoire urbanisé, comme une agglomération ou une municipalité et créé dans le but de protéger contre l'étalement urbain, les terres rurales bordant la collectivité.
{{< /lead >}}

Et si vous aussi, vous voulez manger local et sainement, Tarbes Pour Tous vous propose son programme : la création d’une Ceinture Verte. 
Constat : l’occupation des sols de Tarbes, telle qu’elle ressort de la base de données européenne CLC, est marquée par l’importance des territoires artificialisés (88,6% en 2018), en augmentation par rapport à 1990 (85,6%). Contre 13,8 % de zones agricoles, prairies, espaces verts non agricoles et terres arables.

{{< carousel images="{https://cdn.pixabay.com/photo/2016/12/11/12/02/mountains-1899264_960_720.jpg, gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}

{{< gallery >}}
  <img src="gallery/01.jpg" class="grid-w33" />
  <img src="gallery/02.jpg" class="grid-w33" />
  <img src="gallery/03.jpg" class="grid-w33" />
  <img src="gallery/04.jpg" class="grid-w33" />
  <img src="gallery/05.jpg" class="grid-w33" />
  <img src="gallery/06.jpg" class="grid-w33" />
  <img src="gallery/07.jpg" class="grid-w33" />
{{< /gallery >}}

 {{< gallery >}}
  <img src="gallery/01.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/03.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/04.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/05.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/06.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/07.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

{{< keyword >}} *Super* skill {{< /keyword >}}

{{< keywordList >}}
{{< keyword icon="github" >}} Lorem ipsum dolor. {{< /keyword >}}
{{< keyword icon="code" >}} **Important** skill {{< /keyword >}}
{{< /keywordList >}}

{{< keyword >}} *Standalone* skill {{< /keyword >}}



{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}


{{< mdimporter url="https://raw.githubusercontent.com/nunocoracao/nunocoracao/master/README.md" >}}

{{< swatches "#64748b" "#3b82f6" "#06b6d4" >}}


{{< timeline >}}

{{< timelineItem icon="github" header="header" badge="badge test" subheader="subheader" >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus non magna ex. Donec sollicitudin ut lorem quis lobortis. Nam ac ipsum libero. Sed a ex eget ipsum tincidunt venenatis quis sed nisl. Pellentesque sed urna vel odio consequat tincidunt id ut purus. Nam sollicitudin est sed dui interdum rhoncus. 
{{< /timelineItem >}}


{{< timelineItem icon="code" header="Another Awesome Header" badge="date - present" subheader="Awesome Subheader" >}}
With html code
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="star" header="Shortcodes" badge="AWESOME" >}}
With other shortcodes
{{< gallery >}}
  <img src="gallery/01.jpg" class="grid-w33" />
  <img src="gallery/02.jpg" class="grid-w33" />
  <img src="gallery/03.jpg" class="grid-w33" />
  <img src="gallery/04.jpg" class="grid-w33" />
  <img src="gallery/05.jpg" class="grid-w33" />
  <img src="gallery/06.jpg" class="grid-w33" />
  <img src="gallery/07.jpg" class="grid-w33" />
{{< /gallery >}}
{{< /timelineItem >}}

{{< timelineItem icon="code" header="Another Awesome Header">}}
{{< github repo="nunocoracao/blowfish" >}}
{{< /timelineItem >}}

{{< /timeline >}}

{{< alert "twitter" >}}
Don't forget to [follow me](https://twitter.com/nunocoracao) on Twitter.
{{< /alert >}}

{{< alert icon="fire" cardColor="#e63946" iconColor="#1d3557" textColor="#f1faee" >}}
This is an error!
{{< /alert >}}

{{< button href="#button" target="_self" >}}
Call to action
{{< /button >}}


