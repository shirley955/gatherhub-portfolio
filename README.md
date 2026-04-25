# GatherHub

GatherHub is a spatial data story that investigates how food-related community activity connects to physical space in London. Built as a prototype web application, it brings together data on community venues, shared kitchens, and food-led events to reveal the spatial conditions under which everyday food practices can become shared, visible, and collectively sustained.

---
## Context of prototype

For many of London's urban newcomers, e.g. international students, migrant workers, diaspora communities, food insecurity is not simply about access to food. It is about the absence of spatial infrastructure that would allow private food practices to become shared ones. People may possess rich culinary traditions and a desire to cook and eat together, but lack access to kitchens, halls, or community spaces where this can happen. The problem is fundamentally spatial: it concerns the availability, accessibility, and visibility of places that can host food-related social activity.

Existing information about these spaces and activities is fragmented across platforms, inconsistently structured, and often invisible to the people who need it most. GatherHub addresses this gap by linking events to the places where they happen, making the relationship between community food practice and urban infrastructure legible and navigable.

---

## Conceptual Framing

Conceptual Framing

This project draws on the concept of urban commons — shared urban resources that are collectively used and, in their fullest form, collectively governed. We treat community food spaces as potential commons: the resources exist (kitchens, halls, community centres), and communities of practice form around them (organisers, participants, venue hosts). However, the governance dimension — who decides the rules, who allocates access, how conflicts are resolved — remains largely absent from the current landscape.

GatherHub does not claim to be a commons platform. Rather, it functions as a diagnostic tool: a spatial data story that asks where in the city the conditions for commons-based food practice are forming, and where infrastructure gaps or data fragmentation prevent them from emerging. The prototype sits deliberately at the boundary between an information platform and a commons-enabling tool, and this tension is itself part of the story it tells.

We also frame the prototype as a threshold — a transitional space that mediates between private food practice (cooking alone, eating at home) and shared community activity (communal meals, food workshops, cultural exchanges). The design supports both discovery (finding events and venues nearby) and initiation (submitting new events and linking them to spaces), so that users are not only consumers of information but potential contributors to the community knowledge base.

## Project Overview

Many everyday community activities, such as shared meals, workshops, and small gatherings, depend on access to appropriate spaces. However, information about these spaces and their associated events is often split across different platforms.

This project investigates how linking **events to places** can support:

- a clearer understanding of where community activity happens
- easier navigation between joining an event and finding a space to host one
- better visibility for local food-related practices

The prototype focuses on **food-led activity** as a specific and observable entry point into community life.

---

## Key Features

Features

- **Map-based spatial exploration** of community venues across London, showing where food-related infrastructure is concentrated and where gaps exist

- **Event browsing** with filtering and partial linkage to physical spaces, revealing the connective tissue between activities and places

- **Place detail page** displaying venue characteristics, facilities, and associated activity history
Event submission interface allowing users to contribute new activities and associate them with known venues — a step toward participatory data production

- **Social connectivity visualisation** illustrating the network structure between events, venues, and communities- 

The interface is designed to support both:

- users looking to join existing activities  
- organisers identifying suitable spaces for hosting  

---

## Data and Linking Approach

Data was compiled from multiple publicly available event platforms and manually curated venue datasets. Due to the inherently fragmented nature of community activity data in London:

- Only a subset of events can be reliably linked to specific venues
- Many events contain incomplete or ambiguous location information
- Venue data varies in quality, completeness, and currency

As a result, the platform uses **partial event-place linking**, where connections are made only when the relationship is sufficiently clear.


We treat this partial event–place linkage not merely as a technical limitation but as a substantive finding. The incompleteness of our data reflects a structural reality: much of London's community food activity exists in a data operating outside the reach of formal information systems. This fragmentation is itself part of the spatial data story GatherHub tells: it reveals how community infrastructure remains invisible to the data architectures that increasingly shape urban governance and resource allocation.

---

## Scope

Scope and Limitations
The current prototype focuses on food-related community activity and small-scale, locally hosted events (shared meals, cooking workshops, food exchanges) within London. It does not attempt to provide exhaustive event listings, real-time data, or fully automated event–venue matching.

Key limitations include:

- **Partial linkage:** event–place connections are incomplete and partially manual, reflecting the fragmented state of source data
- **Temporal dynamics:** the prototype does not currently account for recurring events, cancellations, or seasonal variation  
- **Representational gaps:** communities that do not use digital platforms, or that deliberately avoid digital visibility, remain absent from the dataset — a concern we address in our design document's ethical reflection

It does not attempt to provide:

- a complete or exhaustive event listing  
- fully verified or real-time data coverage  
- automated large-scale matching between all events and venues  

These limitations are acknowledged as integral to the design investigation.

---

## Urban Context

This project sits within a broader urban context where access to shared spaces is unevenly distributed, where informal community activities are systematically underrepresented in formal data systems, and where participation in local life is shaped by both social networks and spatial availability. 

- Access to shared spaces is uneven across neighbourhoods  
- Informal and small-scale community activities are often underrepresented in formal data systems  
- Participation in local life is shaped by both **social networks and spatial availability**  

By foregrounding the relationship between **food practices and physical space**, GatherHub contributes to ongoing discussions around **community infrastructure, spatial equity, and the politics of urban data visibility** includes:

- How everyday activities are spatially situated  
- How infrastructure (such as kitchens and community venues) supports social interaction  
- How data fragmentation can obscure opportunities for participation  

---

## Future Directions

- Improved matching methods between events and venues using spatial proximity and text analysis
- Incorporation of additional data sources (council venue registries, community organisation directories)
- Indicators of data confidence and linkage reliability to communicate uncertainty transparently
- **Exploration of participatory governance features** — enabling communities to collectively manage venue information and access rules
