---
############################################################
# Card view on home page
############################################################
# Should the project show up on the home page
show: true
# The order the project card will show up on the home page
order: 13
# Image for the project card
cardImage: {
  src: "../images/materialx-teapot-lion/overview.png",
  alt: "MaterialX Teapot and Lion main image",
}
# The buttons that will show up on the project card
buttons: [
  {
    text: "DOWNLOADS PAGE",
    url: "materialx-teapot-lion",
    type: "primary"
  },
  {
    text: "GITHUB REPOSITORY",
    url: "https://github.com/DigitalProductionExampleLibrary/MaterialXTeapotLion",
    type: "primary"
  },
]
# The description of the project card
description: "The MaterialX Teapot and Lion are MaterialX assets created by NVIDIA as complex, production-style reference materials. Originally used to showcase neural materials, the assets are provided here as MaterialX shader graphs built from standalone BSDFs assembled with layer and mix nodes."
descriptionLinks: {
  text: "",
  url: ""
}

############################################################
# Article / Blog View
############################################################

# The layout file the blog page is using
layout: "../../layout/BlogPostLayout4.astro"
# Title of the blog page
title: "MaterialX Teapot and Lion"
# Used mainly for the Breadcrumbs
titleAlt: "MaterialX Teapot and Lion"
# The url of the blog page
url: "materialx-teapot-lion"
# The cover image of the blog page
coverImage: {
  src: "../images/materialx-teapot-lion/overview.png",
  alt: "MaterialX Teapot and Lion main image",
}
# The image caption under the cover image
imageCaption: {
  # Text is separated by sections to allow links to be added in. <text> <link> <text>
  text: [
    "The MaterialX Teapot and Lion are MaterialX assets created by NVIDIA as complex, production-style reference materials. Originally used to showcase neural materials, the assets are provided here as MaterialX shader graphs built from standalone BSDFs assembled with layer and mix nodes. The assets use a modular graph structure, combining multiple BSDF components with individual texture inputs, normal maps, and layer-specific controls. They demonstrate a range of MaterialX features, including different normal maps applied to individual BSDFs, UDIM-based texture layouts with 4K to 8K texture maps, blended material responses, and inter-layer effects.",
  ],
  # Sample text links that would go in the caption if any. If not remove them like this:
  # {
  #   text: "",
  #   link: ""
  # }
  textLinks: [{
    text: "",
    link: ""
  },
  {
    text: "",
    link: ""
  }]
}

# The extra image gallery
# [] []
# [] []
otherImages: [
  "../images/materialx-teapot-lion/teapot.png", 
  "../images/materialx-teapot-lion/lion.png", 
  "../images/materialx-teapot-lion/teapot_closeup.png", 
  "../images/materialx-teapot-lion/teapot_closeup2.png",
  "../images/materialx-teapot-lion/teapot_closeup3.png",
  "../images/materialx-teapot-lion/lion_closeup.png",
  "../images/materialx-teapot-lion/lion_closeup2.png",
  "../images/materialx-teapot-lion/lion_closeup3.png",
]

# The download section of the blog
downloadSection: {
  title: "Downloadable Packages:",
  subtext: "By downloading any of these files, you agree to the terms of the license linked below.",
  licenseButtonText: "ASWF Asset License",
  licenseButtonLink: "materialx-teapot-lion/materialx-teapot-lion-license",
  # This header is only if the table needs a header < Please see Intel page for example of that >
  downloadTableHeader: "",

  # The download links and button setup for the download table.
  downloads: [
  {
    buttons: [
      {
        text: "GITHUB REPOSITORY",
        url: "https://github.com/DigitalProductionExampleLibrary/MaterialXTeapotLion",
        type: "primary",
      },
      {
        text: "DOWNLOAD",
        url: "https://github.com/DigitalProductionExampleLibrary/MaterialXTeapotLion/archive/refs/tags/v1.0.zip",
        type: "primary",
      }
    ],
    size: "1.8 GB",
    description: "",
    descriptionBold: "MaterialX Teapot and Lion - v.1.0",
    extraDescription: "The primary MaterialX Teapot and Lion assets. Contains the full MaterialX material description with 4K to 8K texture maps, assigned to USD low-resolution model geometry with basic lighting and camera setup. Clone the repository, or download the zip archive directly.",
  },
  {
    buttons: [{
      text: "COMING SOON",
      url: "https://dpel-assets.aswf.io/materialx-teapot-lion/lion_statue_hq.usd",
      type: "primary",
    }],
    size: "1.9 GB",
    description: "",
    descriptionBold: "Lion High Resolution Geometry - v.1.0",
    extraDescription: "Optional high resolution Lion model geometry as USD. Can be dropped into the main asset as a high-res geometry variant.",
  }
  ]
}
---
