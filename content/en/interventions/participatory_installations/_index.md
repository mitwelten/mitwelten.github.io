---
title: Participatory Installations
---

{{< blocks/cover title="PARTICIPATORY INSTALLATIONS" image_anchor="top" height="full" color="gray" >}}
{{< /blocks/cover >}}



<!-- New Section -->

{{% blocks/section color="primary" %}}
<div class="mx-auto">
    <p class="text-column">
        Based on our IoT Toolkit, we experimented with different forms of displaying  sensor-measured data sets with multimedia features to create an informed responsive environment. New Media Art was relevant to this because it often pursues strategies in which data sets are prepared and reformatted in such a way that they can become more accessible to the public. Also, the term Ambient Information Systems should be mentioned here, since it describes physical, tangible representations of information in the environment. By extending the IoT Toolkit with new actuator nodes for light (color LED lamps), sound (bluetooth speakers) and a physical animation (direction indicator), we developed participative and guiding concepts for open spaces. The actuators transfer sensor values back into the physical environment in a dynamic-regulatory manner and thus contribute to the design of an environment with a certain autonomous agency.
    </p>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="secondary" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">SENSING WITH TREES</h3>
    <h4 class="text-center fst-italic mb-5">
        How can passers-by be made aware of critical ecological issues by artistic means and invited to participate and thus take responsibility?
    </h4>
    <br>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <h4>Situation and ecological challenge</h4>
            <p class="justify">
                With the media artistic installation Sensing with Trees we intended to address the consequences of climate change in urban areas by making it more tangible based on the specific situation of local campus residents. We gave the neighboring trees on campus a voice: When the soil was very dry, they were enabled to draw attention to their plight. A watering can, which was positioned next to them, invited passers-by to water the trees, whereupon the moaning fell silent. 
            </p>
            <h4 class="mt-3">Key Concepts</h4>
            <p class="justify">
                The implemented hardware components were part of the <a href="/mitwelten-website/docs/MW_IOT_TOOLKIT.pdf" target="_blank">IoT Toolkit</a> and included sensors for moisture and motion as well as media players and loudspeakers. The humidity sensors were buried in the ground to record soil moisture, the motion sensors fixed to the tree trunks to capture the presence of passers-by and the media players and loudspeakers hung in the tree branches to play different types of tree voices. The recorded sensor values were analyzed in real time by processors and simple decisions were made: “If a person passes close enough by the tree and the soil moisture is below a minimum threshold, then sound files are played via the loudspeakers.
                The installation was not only intended to raise awareness of the critical climate situation in heavily sealed areas, but also to encourage responsible action and cross-species collaboration. Most of the passers-by, however, did not perceive the transmitted message, although we experimented with sound files of different levels of abstraction. The approach would need to be introduced culturally, which could be achieved through media information, information boards and a longer implementation for the local communities.
            </p>
            <p class="justify mt-5">
                A more detailed description of the installation and the findings are presented in the publication <strong>'Mitwelten. Media-ecological Design Strategies for Improving Peri Urban Biodiversity'</strong>. (Coming soon!)
            </p>
        </div>
        <div class="col-md-6 order-md-first">
            <figure>
                <img src="/mitwelten-website/images/interventions/participatory_installations/LTrees01.jpg" width="100%" alt="Speakers of the installation “Sensing with Trees”, with which the trees are given a voice.">
                <figcaption><p class="text-end">Speakers of the installation “Sensing with Trees”, with which the trees are given a voice.</p></figcaption>
            </figure>
            <figure>
                <img src="/mitwelten-website/images/interventions/participatory_installations/LTrees02.jpg" width="100%" alt="The moisture sensor measures the dryness in the soil and registers when the tree is watered by passers-by.">
                <figcaption><p class="text-end">The moisture sensor measures the dryness in the soil and registers when the tree is watered by passers-by.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="blue" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">GUIDANCE SYSTEM</h3>
    <h4 class="text-center fst-italic mb-5">
        How can people and animals be guided away from tricky situations or pointed to interesting phenomena as gently as possible using an IoT guidance system?
    </h4>
    <br>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <h4>Situation and ecological challenge</h4>
            <p class="justify">
                The guidance system is based on networked sensors of the <a href="/mitwelten-website/docs/MW_IOT_TOOLKIT.pdf" target="_blank">IoT Toolkit</a> (cameras, audio-loggers, PAX-counters) that are installed in the outdoor space.
            </p>
            <h4 class="mt-3">Key Concepts</h4>
            <p class="justify">
                The processed measurement data are presented by means of an ambient information system with networked actuators (loudspeakers, lamps, and motors), as well positioned in the outdoor space, to have an audiovisual and physical effect on the environment. In this way, human, animal or plant activities can be recorded and decisions can be made depending on the situation as to whether a conflict between humans and nature could be avoided or whether the phenomenon could be used to sensitize people to nature and foster cohabitation. Based on audiovisual feedback, such as softly flashing lights or sound signals, the environment is given the opportunity to gently guide people or vehicles through the environment and distribute them. 
                Also, a map-based deployment software for the planning and maintenance of the networked IoT system was prototyped. It enables the monitoring of already installed IoT nodes in the field and the linking with simulated, planned nodes. 
                The use of light and sound in a peri-urban environment may not be as disturbing as in untouched nature, but despite this, the approach was viewed very critically from a biological point of view. Design questions arose as to how and where the media indicators would work best and be least disturbing.
            </p>
            <p class="justify mt-5">
                A more detailed description of the system and the findings are presented in the publication <strong>'Mitwelten. Media-ecological Design Strategies for Improving Peri Urban Biodiversity'</strong>. (Coming soon!)
            </p>
        </div>
        <div class="col-md-6">
            <figure>
                <img src="/mitwelten-website/images/interventions/participatory_installations/Leitsystem01.jpg" width="100%" alt="Motorized pointer actuator (prototype) from the IoT toolkit, mounted on a fence for visitor guidance.">
                <figcaption><p>Motorized pointer actuator (prototype) from the IoT toolkit, mounted on a fence for visitor guidance.</p></figcaption>
            </figure>
            <figure>
                <img src="/mitwelten-website/images/interventions/participatory_installations/Leitsystem02.png" width="100%" alt="Screenshot of the software prototype for planning visitor guidance with set up and virtual sensors and actuators.">
                <figcaption><p>Screenshot of the software prototype for planning visitor guidance with set up and virtual sensors and actuators.</p></figcaption>
            </figure>
        </div>
    </div>

{{% /blocks/section %}}
