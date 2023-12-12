---
title: "Piet"
date: 2023-12-01T12:21:57-09:00
featured_image: "/images/telarTN.png"
description: "This is a page under construction for Piet"
isCard: false
isPost: true
buttonText: "Learn More"
---
{{< pdf "/pdf/telarM4L-ug.pdf" >}}
{{< pdf "/pdf/telarApp-ug.pdf" >}}
{{< gumroad "https://flaviogaete.gumroad.com/l/telar" >}}

![Telar - A Dynamic MIDI mapper for the Sensel Morph Thunder overlay](/images/telarTN.png)

**Telar** is a dynamic MIDI mapper for [Sensel Morph’s Thunder Overlay.](https://morph.sensel.com/pages/buchla-thunder-overlay)
Thunder’s controls are split into a simple symmetric setup and an intuitive structure.
It also features a sophisticated preset system, designed with live performance in mind. 
Each slider can be mapped to any one note (or chord), XYZ control and MIDI channel. 
Telar comes as a suite of Max for Live devices (a standalone app is also in the works, see video below).

{{< spacer >}}
{{< youtube gEsP6IZ8xK4 >}}

## FIRST TITLE

![Telar routing features](telarRouting.png)

The Sensel Morph, with the Thunder Overlay, is connected to a MIDI track in Live, with an instance of Telar. Another MIDI track (or set of tracks) will hold an instance of the Telar Bus device, which is responsible for sending the corresponding MIDI out. The outgoing signal can be fed into an instrument in Live (it also works with MPE if you use inter-application MIDI communication), or an external MIDI output; Telar also comes with a suite of additional devices that allow you to convert MIDI control data or apply remote mappings so that you can control any parameter in Live.

---

## System Requirements

M4L devices built with Max 8.1.10. & recommended for Live 11.
[License Information](/license)

{{< spacer >}}
{{< button "post-button-accent" "https://flaviogaete.gumroad.com/l/telar" "_blank" "Buy" >}}


