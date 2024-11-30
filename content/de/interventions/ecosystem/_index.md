---
title: Ecosystem
---

{{< blocks/cover title="CITIZEN SCIENCE-BASIERTE ÖKOSYSTEMSTUDIEN" image_anchor="top" height="full" color="gray" >}}
{{< /blocks/cover >}}



<!-- New Section -->

{{% blocks/section color="primary" %}}
<div class="mx-auto">
    <p class="text-column">
Ein Forschungsansatz im Mitwelten-Projekt basierte auf naturwissenschaftlichen Prinzipien. Durch das Monitoring der Ökosysteme der drei Feldstudien wollten wir Erkenntnisse über die Qualität der Biodiversität in den stadtnahen Lebensräumen gewinnen. Da es nicht möglich ist, den gesamten Naturreichtum zu messen und zu kartieren, haben wir uns entschieden, das Vorkommen von Leitarten oder -familien zu analysieren: fünf Morphospezies bestäubender Insekten und die Vogelarten. Um das Bild zu vervollständigen, wurde auch die Anwesenheit des Menschen untersucht, da Menschen einen erheblichen Einfluss auf stadtnahe Gebiete haben und wir sie als gleichberechtigte Akteure der Mitwelt behandeln wollten. Durch die Verwendung derselben Systeme unter standardisierten Bedingungen in verschiedenen Lebensräumen, konnten wir Aussagen über die Standorte machen und diese vergleichen. Die Experimente für die Untersuchungen wurden im interdisziplinären Team umgesetzt und die Sensorsysteme so entwickelt, dass sie ökologische Fragen bestmöglich beantworten und den Verwaltungsaufwand minimieren.
    </p>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="secondary" %}}

<div class="mx-auto"">
    <h3 class="text-center mb-5">VOGELVIELFALT</h3>
    <h4 class="text-center fst-italic mb-5">
Wie können Vogelarten in unterschiedlichen Habitattypen mit Hilfe umfangreicher Audio-Logger Aufnahmen und Open Source ML-Modellen bestimmt und verglichen werden?
    </h4>
    <div class="row px-0 gx-5">
        <div class="col-md-6">
            <p class="justify">
Um mehr über die lokale Vogelwelt zu erfahren, analysierten wir die Untersuchungsgebiete der drei Feldstudien. Zunächst definierten wir Standorte mit unterschiedlichen Lebensraumtypen, zeichneten die Gesangsaktivitäten mit Audiologgern (<a href="https://www.openacousticdevices.info">AudioMoth</a>) auf und analysierten die Vogelarten mithilfe einer Datenpipeline, die auf dem maschinellen Lernmodell (ML) BirdNET basiert. 
            </p>
            <h4 class="mt-3">Datensammlung und Methodik</h4>
            <p  class="justify">
Die Vogelbestimmungen wiesen Fehler auf, die korrigiert werden mussten: Ausschlüsse auf der Grundlage von Ort und Zeit (Zugzeit, Tageszeit, Lebensraumtyp), Überprüfung unwahrscheinlicher Arten anhand von Berichten aus der Vogelbeobachtungs-Community und Überprüfung der Tonaufnahmen durch Citizen Scientists (Vorvalidierung) und Experten unter Verwendung der Open-Source-Software Label Studio. Wir haben die Geräusche, die zu falschen Vogelbestimmungen in den stadtnahen Gebieten führten – diese aber auch als Kakophonie von Geräuschen bereicherten – in fünf Typen eingeteilt: menschliche Stimmen oder Artefakte (Anthropophonie), Wettergeräusche (Geophonie), andere Tierklassen (z. B. Wasserfrösche) und Vogelarten (Biophonie) (Krause 2015).
            </p>
            <h4 class="mt-3">Ergebnisse und Erkenntnisse</h4>
            <p  class="justify">
Das Ziel bestand darin, eine ML-Pipeline für die Analyse des gesammelten Big Data zu entwickeln, die Vogelvielfalt zu bestimmen und die ökologische Qualität der unterschiedlichen stadtnahen Lebensräume zu vergleichen. Darüber hinaus waren wir daran interessiert, die verschiedenen Klanglandschaften zu charakterisieren und die Möglichkeiten von ML-Anwendung zur Verbesserung des alltäglichen Klangerlebnisses der Öffentlichkeit zu erforschen.
            </p>
            <p class="justify mt-5">
Weitere Informationen finden Sie in der frei zugänglichen Publikation <strong>„Vogelvielfalt in stadtnahen Gebieten der Stadt Basel“</strong>. (Erscheint in Kürze!)
            </p>
        </div>
        <div class="col-md-6 order-md-first">
            <figure>
                <img src="/images/interventions/ecosystem/BirdDiversity1.jpg" width="100%" alt="‘AudioMoth’ Audio-Logger in getarntem Gehäuse, mit QR-Code für interessierte Passant*innen.">
                <figcaption><p class="text-end">‘AudioMoth’ Audio-Logger in getarntem Gehäuse, mit QR-Code für interessierte Passant*innen.</p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/BirdDiversity2.jpg" width="100%" alt="Karte mit den Standorten der Audiologger im Jahr 2021 in unterschiedlichen Geländetypen.">
                <figcaption><p class="text-end">Karte mit den Standorten der Audiologger im Jahr 2021 in unterschiedlichen Geländetypen.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="teal" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">BESTÄUBERVIELFALT</h3>
    <h4 class="text-center fst-italic mb-5">
        Wie können bestäubende Insekten durch ML-Analyse von in regelmässigen Abständen aufgenommenen Fotos bestimmt werden?
    </h4>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <p class="justify">
                Um mehr über die lokalen Insektengemeinschaften zu erfahren, analysierten wir die Untersuchungsgebiete der drei Feldstudien und definierten Standorte in verschiedenen Lebensraumtypen. Gemäss entomologischen Standards verwendeten wir Kameras, die über Topfblumen befestigt waren, um in regelmässigen Abständen Blüten-besuchende Insekten zu fotografieren. 
            </p>
            <h4 class="mt-3">Datensammlung und Methodik</h4>
            <p class="justify">
                Wir unterschieden zwischen fünf verschiedene Morphospezies: Honigbiene, Wildbiene, Hummel, Schwebfliege und Fliege. Ein auf YOLOv5 basierendes Machine Learning (ML) Modell wurde verwendet, um zunächst die Blüten auf den Fotos und anschliessend die Insekten auf den Blüten zu identifizieren.
            </p>
            <h4 class="mt-3">Ergebnisse und Erkenntnisse</h4>
            <p class="justify">
                Ziel war es, unseren Phytometer-Ansatz zu entwickeln und zu untersuchen und die ökologischen Qualitäten der Orte und Lebensraumtypen innerhalb der Feldstudien zu vergleichen. Wir gewannen auch Einblicke in die Montage und Wartung von Monitoring-Infrastrukturen und in Datenvalidierungsprozesse unter Einbeziehung von Citizen Scientists.
            </p>
            <p class="justify mt-5">
Weitere Informationen finden Sie in der Open-Access-Publikation <strong>„Vogelvielfalt in stadtnahen Gebieten der Stadt Basel“</strong>. (In Kürze verfügbar!)
            </p>
        </div>
        <div class="col-md-6">
            <figure>
                <img src="/images/interventions/ecosystem/PollinatorDiversity1.jpg" width="100%" alt="Pollinator-Installationen nach einem interdisziplinären Montageworkshop, bereit für die Montage im Feld.">
                <figcaption><p>Pollinator-Installationen nach einem interdisziplinären Montageworkshop, bereit für die Montage im Feld.</p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/PollinatorDiversity2.jpg" width="100%" alt="Geöffnete selbst zusammengebaute Kamera, montiert an einer Stange über einem Topf mit Lockpflanzen.">
                <figcaption><p>Geöffnete selbst zusammengebaute Kamera, montiert an einer Stange über einem Topf mit Lockpflanzen.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}





<!-- New Section -->

{{% blocks/section color="yellow" %}}

<div class="mx-auto">
    <h3 class="text-center mb-5">MENSCHLICHE PRÄSENZ</h3>
    <h4 class="text-center fst-italic mb-5">
        Wie kann die Anwesenheit von Menschen in Naherholungs- und Naturschutzgebieten festgestellt werden?
    </h4>
    <div class="row align-items-start px-0 gx-5">
        <div class="col-md-6 align-items-end">
            <p class="justify">
                Neben dem biologischen Monitoring von Vögeln und Insekten haben wir auch die Anwesenheit von Menschen erfasst, da diese als gleichgestellte Lebensraum-Aktanten behandelt werden sollten. 
            </p>
            <h4 class="mt-3">Datensammlung und Methodik</h4>
            <p class="justify">
            Das Hauptziel bestand darin, die Anzahl anonymisierter Personen an bestimmten Orten zu unterschiedlichen Zeiten zu ermitteln, um ihren möglichen Einfluss auf die Ökosysteme zu untersuchen. Gemeinsam mit der Heide Kommission und den Parkrangern entwarfen wir ein Netzwerk von <a href="https://github.com/cyberman54/ESP32-Paxcounter" target="_blank">PAX-Zählern</a>, das von interdisziplinären Teams zusammengebaut, installiert und gewartet wurde. 
            </p>
            <h4 class="mt-3">Ergebnisse und Erkenntnisse</h4>
            <p class="justify">
                Ziel war es herauszufinden, welche Orte wie oft frequentiert wurden, wie viele Menschen sich in der Nähe besonders fragiler Schutzzonen aufhielten, ob der neue Badeplatz den Besucherdruck auf einen inoffiziellen Badeplatz im Naturschutzgebiet verringerte und ob die Massnahmen zur Besucherlenkung wirksam waren.
            </p>
            <p class="justify mt-5">
Weitere Informationen finden Sie in der Open-Access-Publikation <strong>„Bird Diversity in Peri-urban Areas of the City of Basel“</strong>. (In Kürze verfügbar!)
            </p>
        </div>
        <div class="col-md-6 order-md-first">
            <figure>
                <img src="/images/interventions/ecosystem/HumanPresence1.jpg" width="100%" alt="PAX-Counter ausser Reichweite an Baum neben dem Biberpfad montiert.">
                <figcaption><p class="text-end">PAX-Counter ausser Reichweite an Baum neben dem Biberpfad montiert.</p></figcaption>
            </figure>
            <figure>
                <img src="/images/interventions/ecosystem/HumanPresence2.png" width="100%" alt="Heat-Map der menschlichen Präsenz im gesamten Untersuchungsgebiet.">
                <figcaption><p class="text-end">Heat-Map der menschlichen Präsenz im gesamten Untersuchungsgebiet.</p></figcaption>
            </figure>
        </div>
    </div>
</div>

{{% /blocks/section %}}
