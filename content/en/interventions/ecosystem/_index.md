---
title: Ecosystem
---

{{< blocks/cover title="CITIZEN SCIENCE BASED ECOSYSTEM STUDIES" image_anchor="top" height="full" color="gray" >}}
{{< /blocks/cover >}}



<!-- New Section -->

{{% blocks/section color="primary" %}}
<div class="mx-auto">
    <p class="text-column">
        One research approach in the <em>Mitwelten project</em> was based on natural <strong>science principles</strong>. By monitoring the ecosystems of the three field studies, we wanted to gain insight into the quality of biodiversity in the (peri-)urban habitats. Since it is not possible to measure and map the full richness of nature, we decided to analyze the presence of indicator species or families: five types of morphospecies of pollinating insects and the bird species. To complete the picture, human presence was also examined, as humans have a significant influence on (peri-)urban sites and to treat them as equal actors of the _Mitwelt_. By using the same systems in standardized circumstances in different habitats, we were able to make statements about the locations and compare them. The experiments for the investigations were carried out by the interdisciplinary team and the sensor systems were developed to best answer ecological questions and minimize management efforts.
    </p>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="secondary" %}}

<div class="mx-auto"">
    <h3 class="text-center mb-5">BIRD DIVERSITY</h3>
    <h4 class="text-center fst-italic mb-5">
        How can bird species in different habitat types be identified and compared using audio logger recordings and open source ML models?
    </h4>
    <div class="row px-0 gx-5">
        <div class="col-md-6">
            <p class="justify">
                To learn more about the local bird life, we analyzed the three Field Study Sites. We first defined locations with different habitat types, recorded the singing activities with audio loggers (<a href="https://www.openacousticdevices.info">AudioMoth</a>), and analyzed the bird species using a data pipeline based on the machine learning (ML) model BirdNET. 
            </p>
            <h4 class="mt-3">Data Collection and Methods</h4>
            <p  class="justify">
                The species identifications showed errors that had to be corrected: exclusions based on time and location (migratory season, time of day, habitat type), verification of improbable species with reports from the birding community, and sound recording verification by citizen scientists (prevalidation) and experts using the open-source software Label Studio. We categorized the sounds that led to wrong bird identifications in the peri-urban environment – but also enriched it as a cacophony of sounds – into five types: human voices or artifacts (anthropophony), weather sounds (geophony), other animal classes (e.g. water frog) and bird species (biophony), (Krause 2015). 
            </p>
            <h4 class="mt-3">Objectives and Findings</h4>
            <p  class="justify">
                The goal was to develop an ML pipeline for the analysis of the collected big data, to identify the bird species and to compare the quality of the different peri-urban habitats. In addition, we were interested in characterizing the different soundscapes and to explore the possibilities of applying ML to improve the public’s everyday sound experience.
            </p>
            <p class="justify mt-5">
                For further information please read the open access publication <strong>‘Bird Diversity in Peri-urban Areas of the City of Basel’</strong>. (Coming soon!)
            </p>
        </div>
        <div class="col-md-6 order-md-first">
            <figure>
                <img src="/images/interventions/ecosystem/BirdDiversity1.jpg" width="100%" alt="'AudioMoth' audio logger in camouflaged casing, with QR code for interested passers-by.">
                <figcaption><p class="text-end">'AudioMoth' audio logger in camouflaged casing, with QR code for interested passers-by.</p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/BirdDiversity2.jpg" width="100%" alt="Map with the locations of the audio loggers in 2021 in different types of terrain.">
                <figcaption><p class="text-end">Map with the locations of the audio loggers in 2021 in different types of terrain.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="teal" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">POLLINATOR DIVERSITY</h3>
    <h4 class="text-center fst-italic mb-5">How can pollinating insects be determined by ML analysis of photos taken at regular intervals?</h4>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <p class="justify">
                To learn more about the local insect communities, we analyzed the Field Study Sites and defined locations in different habitat types. In accordance with entomological standards, we used cameras mounted above potted flowers to take photos of flower-visiting insects at regular intervals.
            </p>
            <h4 class="mt-3">Data Collection and Methods</h4>
            <p class="justify">
                We distinguished between five different morphospecies: honey bee, wild bee, bumblebee, hoverfly, and fly. A YOLOv5-based machine learning (ML) model was used to first identify the blossoms in the photos and subsequently the insects on the blossoms. 
            </p>
            <h4 class="mt-3">Objectives and Findings</h4>
            <p class="justify">
                The main goal was to develop and examine our phytometer approach and to compare the ecological qualities of the places and habitat types within the field studies. We also gained insights into the assembly and maintenance of biological monitoring infrastructures and data validation processes involving citizen scientists.
            </p>
            <p class="justify mt-5">
                For further information please read the open access publication <strong>‘Bird Diversity in Peri-urban Areas of the City of Basel’</strong>.<br>(Coming soon!)
            </p>
        </div>
        <div class="col-md-6">
            <figure>
                <img src="/images/interventions/ecosystem/PollinatorDiversity1.jpg" width="100%" alt="Pollinator installations after an interdisciplinary assembly workshop, ready for setup in the field. ">
                <figcaption><p>Pollinator installations after an interdisciplinary assembly workshop, ready for setup in the field. </p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/PollinatorDiversity2.jpg" width="100%" alt="Open self-assembled camera, mounted on a pole above a pot of attractant plants.">
                <figcaption><p>Open self-assembled camera, mounted on a pole above a pot of attractant plants.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}





<!-- New Section -->

{{% blocks/section color="yellow" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">HUMAN PRESENCE</h3>
    <h4 class="text-center fst-italic mb-5">
        How can human presence be identified in local recreation areas and nature reserves?
    </h4>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <p class="justify">
                In addition to biological monitoring through sampling of birds and insects, we also recorded the presence of humans, since they should be treated as equal habitat actants. 
            </p>
            <h4 class="mt-3">Data Collection and Methods</h4>
            <p class="justify">
                The main objective was to determine the number of anonymized individuals at specific locations at different times in order to study their possible influence on the ecosystems. Together with the nature conservation commission (Heide Kommission) and the park rangers, we designed a network of <a href="https://github.com/cyberman54/ESP32-Paxcounter" target="_blank">PAX counters</a> that was assembled and maintained by interdisciplinary teams. 
            </p>
            <h4 class="mt-3">Objectives and Findings</h4>
            <p class="justify">
                The aim was to find out which places were most frequented, how many people were near vulnerable conservation areas, if the new bathing area reduced visitor pressure on an unofficial bathing area in the nature reserve, and if visitor management measures were effective.
            </p>
            <p class="justify mt-5">
                For further information please read the open access publication <strong>‘Bird Diversity in Peri-urban Areas of the City of Basel’</strong>. (Coming soon!)
            </p>
        </div>
        <div class="col-md-6 order-md-first">
            <figure>
                <img src="/images/interventions/ecosystem/HumanPresence1.jpg" width="100%" alt="PAX counter mounted out of reach on tree next to the beaver trail.">
                <figcaption><p class="text-end">PAX counter mounted out of reach on tree next to the beaver trail.</p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/HumanPresence2.png" width="100%" alt="Heat map of human presence in the entire study area.">
                <figcaption><p class="text-end">Heat map of human presence in the entire study area.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}
