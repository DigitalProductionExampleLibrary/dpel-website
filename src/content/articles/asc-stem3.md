---
############################################################
# Card view on home page
############################################################
# Should the project show up on the home page
show: true
# The order the project card will show up on the home page
order: 12
# Image for the project card
cardImage: {
  src: "../images/StEM3/hero.jpg",
  alt: "Stem 3 still image",
}
# The buttons that will show up on the project card
buttons: [
  {
    text: "DOWNLOADS PAGE",
    url: "asc-stem3",
    type: "primary"
  },
  {
    text: "PROJECT HOME",
    url: "https://theasc.com/society/stem3",
    type: "primary"
  }
]
# The description of the project card
description: "The American Society of Cinematographers Motion Imaging Technology Council introduces the next phase of the ASC Standard Evaluation Material projects: ASC MITC StEM3-VP, the third StEM project specifically for in-camera visual effects virtual production LED wall/volume technology. For more information, visit the"
descriptionLinks: {
  text: "ASC StEM3 website.",
  url: "https://theasc.com/society/stem3"
}

############################################################
# Article / Blog View
############################################################
# The layout file the blog page is using
layout: "../../layout/ASCStem3Layout.astro"
# Title of the blog page
title: "ASC StEM3 - Standard Evaluation Material 3"
# Used mainly for the Breadcrumbs
titleAlt: "Standard Evaluation Material 3"
# The url of the blog page
url: "asc-stem3"
# The cover image at the top of the blog
coverImage: {
  src: "../images/StEM3/hero.jpg",
  alt: "ASC Stem 3",
}
# The image caption under the cover image
imageCaption: {
  # Text is separated by sections to allow links to be added in. <text> <link> <text>
  text: [
    "The American Society of Cinematographers Motion Imaging Technology Council introduces the next phase of the ASC Standard Evaluation Material projects: ASC MITC StEM3-VP, the third StEM project specifically for in-camera visual effects virtual production LED wall/volume technology.",
    "Created by the ASC's MITC under the leadership of the Virtual Production committee, the StEM3-VP is a suite of donated assets hosted by the Academy Software Foundation's Digital Production Library. The suite features multiple Epic Games Unreal Engine pre-built environments donated by top virtual production companies around the world, 2D driving plates, and 2D test elements that a cinematographer may use to test and evaluate a stage before shooting their production on it. The StEM3-VP assets can be used to check the performance and integrity of the LED panels and system functions.",
    "In addition, among the assets is a short scene shot by David Klein, ASC, written by Michael Goi, ASC, ISC and ASC associate member Jay Holben and directed by Holben. \"Warped: CyberCity\" showcases the capabilities of the ICVFX volume technology and provides a visual example using one of the donated assets.",
    "For more information, visit the ",
    "Join the conversation in the #assets channel "
  ],
  # Sample text links that would go in the caption if any. If not remove them like this:
  # {
  #   text: "",
  #   link: ""
  # }
  textLinks: [
  {
    text: "",
    link: ""
  },
  {
    text: "",
    link: ""
  },
  {
    text: "",
    link: ""
  },
  {
    text: "ASC StEM3 website.",
    link: "https://theasc.com/society/stem3"
  },
  {
    text: "on the ASWF Slack.",
    link: "https://slack.aswf.io/"
  }]
}

# The extra image gallery
# [] []
# [] []
otherImages: [
  {
    title: "Asset Gallery",
    captionStyle: "overlay",
    images: [
      { src: "../images/StEM3/gallery1.jpg", caption: "Cybercity" },
      { src: "../images/StEM3/gallery2.jpg", caption: "Base Camp" },
      { src: "../images/StEM3/gallery3.jpg", caption: "Back Alley" },
      { src: "../images/StEM3/gallery4.jpg", caption: "Saloon" },
      { src: "../images/StEM3/gallery5.jpg", caption: "Forest" },
      { src: "../images/StEM3/gallery6.jpg", caption: "Subway Station" },
      { src: "../images/StEM3/gallery7.jpg", caption: "LA Driving Plate" },
      # { src: "../images/StEM3/gallery8.jpg", caption: "Soda Cans" },
      { src: "../images/StEM3/gallery9.jpg", caption: "Color Chart" },
      { src: "../images/StEM3/gallery10.png", caption: "Lightning" },
    ]
  },
  {
    title: '"Warped : Cybercity" short film',
    images: [
      "../images/StEM3/warped1.jpg",
      "../images/StEM3/warped2.jpg",
      "../images/StEM3/warped3.jpg",
      "../images/StEM3/warped4.jpg",
    ]
  }
]

# The download section of the blog
downloadSection: {
  title: "Downloadable Packages:",
  subtext: "By downloading any of these files, you agree to the terms of this license:",
  licenseButtonText: "ASWF Asset License",
  downloadTableHeader: "",
  # The download links and button setup for the download table.
  # 6-column structure: Asset Name | Image | Movie Preview | Description | License | Download + Size
  downloads: [{
    tableHeader: '"Warped : Cybercity"',
    downloadsList: [{
          assetName: '"Warped : Cybercity"',
          thumbnail: "../images/StEM3/warped1.jpg",
          moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Warped-Cybercity/Warped_Cybercity_1920x1080_Rec709_BT1886_5.1ch.mp4",
          description: "Directed by Jay Holben and photographed by David Klein, ASC, <strong>\"Warped : Cybercity\"</strong> is a short sequence that demonstrates the use of the StEM3 Cybercity asset in the context of a full-blown live action, virtual production shoot. See how it was made in the <strong>\"Behind the Scenes\"</strong> below.",
          extraDescription: "Donated by the ASC",
          licenseUrl: "/asc-stem3/asc-stem3-warped-cybercity-license",
          buttons: [{
            text: "DOWNLOAD SDR",
            url: "https://dpel-assets.aswf.io/asc-stem3/Warped-Cybercity/Warped_Cybercity_1920x1080_Rec709_BT1886_5.1ch.mov",
            type: "primary",
            size: "5.4 GiB",
          },
          {
            text: "DOWNLOAD HDR",
            url: "https://dpel-assets.aswf.io/asc-stem3/Warped-Cybercity/Warped_Cybercity_3840x2160_Rec2100_ST2084_500nits_5.1ch.mov",
            type: "primary",
            size: "38.0 GiB",
          }],
        },
        {
          assetName: 'Behind the Scenes',
          thumbnail: "../images/StEM3/warped2.jpg",
          moviePreview: "https://vimeo.com/1210327424",
          description: "A full length deep-dive into the making of StEM3, showcasing the production of “Warped: Cybercity” and the suite of virtual production assets, as well as featuring sit-down interviews with everyone involved in the project as they share their insights on the process and technology.",
          extraDescription: "Donated by the ASC",
          licenseUrl: "/asc-stem3/asc-stem3-warped-cybercity-license",
          buttons: [{
            text: "Preview only",
        }],
        }
      ]
  },
  {
    tableHeader: 'StEM3 Assets : 3D Scenes',
    downloadsList: [{
        assetName: "Cybercity",
        thumbnail: "../images/StEM3/gallery1.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Cybercity.mp4",
        description: "StEM3 <strong>Cybercity</strong> is a 3D asset representing an iconic neon city at night, reminiscent of the cyberpunk culture. It was used in the production of the “Warped : Cybercity” short sequence. StEM3 Cybercity is provided as an Unreal Engine v5.7 asset.",
        extraDescription: "Donated by Craftology",
        licenseUrl: "/asc-stem3/asc-stem3-cybercity-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Cybercity_UE54.zip",
          type: "primary",
          size: "18.0 GiB",
        }],
      },
      {
        assetName: "Forest",
        thumbnail: "../images/StEM3/gallery5.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Forest.mp4",
        description: "StEM3 <strong>Forest</strong> is a 3D asset representing a burnt forest under cloudy sky and intermittent lightning bolts. There is more to discover. StEM3 Cybercity is provided as an Unreal Engine vX.X asset.",
        extraDescription: "Donated by Craftology",
        licenseUrl: "/asc-stem3/asc-stem3-forest-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Forest_UE51.zip",
          type: "primary",
          size: "17.6 GiB",
        }],
      },
      {
        assetName: "Base Camp",
        thumbnail: "../images/StEM3/gallery2.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Base_Camp.mp4",
        description: "StEM3 <strong>Base Camp</strong> is a 3D asset showcasing an himalayan base camp and the surrounding windy landscape of snow capped mountains, complete with tents and a row of flags fluttering in the wind.",
        extraDescription: "Donated by NantStudios",
        licenseUrl: "/asc-stem3/asc-stem3-base-camp-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Base_Camp_UE5x.zip",
          type: "primary",
          size: "5.4 GiB",
        }],
      },
      {
        assetName: "Subway Station",
        thumbnail: "../images/StEM3/gallery6.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Subway_Station.mp4",
        description: "StEM3 <strong>Subway Station</strong> is a 3D asset representing an actual subway station as it is located in Montreal, Canada. Complete with ticket stalls and ATM machine, it can be explored in a few directions.",
        extraDescription: "Donated by MELS Studios and Postproduction",
        licenseUrl: "/asc-stem3/asc-stem3-subway-station-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Subway_Station_UE53.zip",
          type: "primary",
          size: "2.8 GiB",
        }],
      },
      {
        assetName: "Back Alley",
        thumbnail: "../images/StEM3/gallery3.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Back_Alley.mp4",
        description: "StEM3 <strong>Back Alley</strong> is a 3D asset showcasing a suspicious and disorderly back alley, including some parked car and trash of all sorts.",
        extraDescription: "Donated by MELS Studios and Postproduction",
        licenseUrl: "/asc-stem3/asc-stem3-back-alley-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Back_Alley_UE53.zip",
          type: "primary",
          size: "13.9 GiB",
        }],
      },
      {
        assetName: "Saloon",
        thumbnail: "../images/StEM3/gallery4.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Saloon.mp4",
        description: "StEM3 <strong>Saloon</strong> is a 3D asset featuring an interior scene within a western saloon of lore. It comes with the bar, an assortment of liquors, some tables, chairs and a sitting area, all surrounded by second floor balconies on both sides.",
        extraDescription: "Donated by Epic Games, Inc.",
        licenseUrl: "/asc-stem3/asc-stem3-saloon-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/3D_Assets/StEM3_Saloon_UE5x.zip",
          type: "primary",
          size: "24.5 GiB",
        }],
      }
    ]
  },
  {
    tableHeader: 'StEM3 Assets : 2D Plates',
    downloadsList: [
      {
        assetName: "LA Driving Plate",
        thumbnail: "../images/StEM3/gallery7.jpg",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Driving_Plate.mp4",
        description: "StEM3 <strong>Los Angeles Driving Plate</strong> is a 2D asset / short movie loop of a drive through downtown L.A. around the iconic Westin Bonaventure Hotel.",
        extraDescription: "Donated by Spheris Array Systems",
        licenseUrl: "/asc-stem3/asc-stem3-la-driving-plate-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/2D_Assets/StEM3_Driving_Plate.zip",
          type: "primary",
          size: "8.4 GiB",
        }],
      },
      # {
      #   assetName: "Soda Cans",
      #   thumbnail: "../images/StEM3/gallery8.jpg",
      #   moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Soda_Can_Plates.mp4",
      #   description: "Soda cans test element for color accuracy and detail evaluation",
      #   extraDescription: "",
      #   licenseUrl: "/asc-stem3/asc-stem3-soda-cans-license",
      #   buttons: [{
      #     text: "DOWNLOAD - COMING SOON",
      #     url: "https://dpel-assets.aswf.io/asc-stem3/Assets/2D_Assets/StEM3_Soda_Can_Plates.zip",
      #     type: "primary",
      #   }],
      #   size: "442.4 MiB",
      # },
      {
        assetName: "Lightning Plate",
        thumbnail: "../images/StEM3/gallery10.png",
        moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Lightning_Plate.mp4",
        description: "<strong>StEM3 Lightning Plate</strong> showcases lightning strikes on a dark and stormy background. The rapid flashes of lightning can be helpful to visually evaluate the synchronization of video tiles on a virtual production wall. Provided in Unreal Engine 5.7 format.",
        extraDescription: "Donated by Vū Technologies",
        licenseUrl: "/asc-stem3/asc-stem3-lightning-plate-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/2D_Assets/StEM3_Lightning_Plate.zip",
          type: "primary",
          size: "214.9 MiB",
        }],
      },
      # {
      #   assetName: "Color Charts",
      #   thumbnail: "../images/StEM3/gallery9.jpg",
      #   moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Color_Checker.mp4",
      #   description: "<strong>StEM3 Color Charts</strong> includes 2D charts that can be used to evaluate colorimetry and other aspects of a virtual production stage.",
      #   extraDescription: "Public Domain / CC0 1.0<br><br>Disclaimer: \"ColorChecker\" and \"X-Rite\" are registered trademarks of X-Rite, Incorporated (or their respective owners). ASWF, DPEL, StEM3, and the ASC are independent entities and are not affiliated with, sponsored by, or endorsed by X-Rite, Incorporated, Calibrite, or any of their affiliates. References to these trademarks are made solely for the purpose of indicating compatibility and technical specifications.",
      #   licenseUrl: "https://creativecommons.org/publicdomain/zero/1.0/",
      #   buttons: [{
      #     text: "DOWNLOAD",
      #     url: "https://dpel-assets.aswf.io/asc-stem3/Assets/2D_Assets/StEM3_Color_Checker.zip",
      #     type: "primary",
      #     size: "1.4 MiB",
      #   }],
      # },
      {
        assetName: "25 Stop Exposure Chart",
        thumbnail: "../images/StEM3/gallery11.png",
        # moviePreview: "https://dpel-assets.aswf.io/asc-stem3/Assets/asset_previews/StEM3_Color_Checker.mp4",
        description: "<strong>StEM3 25-Stop Exposure Chart</strong> includes a 2D chart that can be used to evaluate the dynamic range, sensor characterization, and other aspects of a virtual production stage.",
        extraDescription: "Donated by TSK Pictures, Inc.",
        licenseUrl: "/asc-stem3/asc-stem3-charts-license",
        buttons: [{
          text: "DOWNLOAD",
          url: "https://dpel-assets.aswf.io/asc-stem3/Assets/2D_Assets/StEM3_UHD-SceneLinear-25_stop_exposure_chart.exr",
          type: "primary",
          size: "49.8 MiB",
        }],
      },
    ]
  }
  ]
}

hideButtons: true
licenseContent: [
  "ASWF Digital Assets License v1.1",
  "StEM3 -- Copyright 2026 -- American Society of Cinematographers -- All rights reserved.",
  "Redistribution and use of these digital assets, with or without modification, solely for education, training, research, software and hardware development, performance benchmarking (including publication of benchmark results and permitting reproducibility of the benchmark results by third parties), or software and hardware product demonstrations, are permitted provided that the following conditions are met:"
]

licenseConditions: [
  "Redistributions of these digital assets or any part of them must include the above copyright notice, this list of conditions and the disclaimer below, and if applicable, a description of how the redistributed versions of the digital assets differ from the originals.",
  "Publications showing images derived from these digital assets must include the above copyright notice.",
  "The names of copyright holder or the names of its contributors may NOT be used to promote or to imply endorsement, sponsorship, or affiliation with products developed or tested utilizing these digital assets or benchmarking results obtained from these digital assets, without prior written permission from copyright holder.",
  "The assets and their output may only be referred to as the Asset Name listed above, and your use of the Asset Name shall be solely to identify the digital assets. Other than as expressly permitted by this License, you may NOT use any trade names, trademarks, service marks, or product names of the copyright holder for any purpose."
]

licenseDisclaimer: 'DISCLAIMER: THESE DIGITAL ASSETS ARE PROVIDED BY THE COPYRIGHT HOLDER "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, ARE DISCLAIMED. IN NO EVENT SHALL COPYRIGHT HOLDER BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THESE DIGITAL ASSETS, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.'
---
