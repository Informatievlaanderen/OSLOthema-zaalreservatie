<h1>Table of Contents</h1>
<ul>
    <li><a href="#aanbod">Aanbod</a>
        <ul>
            <li><a href="#aanbod-class">Class</a></li>
            <li><a href="#aanbod-properties">Properties</a>
                <ul>
                    <li>beleidsdomein</li>
                    <li>beschrijving</li>
                    <li>categorie</li>
                    <li>doelgroep</li>
                    <li>infrastructuur</li>
                    <li>intake</li>
                    <li>gerealiseerdDoor</li>
                    <li>maxAantalDeelnemers</li>
                    <li>medium</li>
                    <li>subcategorie</li>
                    <li>taal</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#individueelaanbod">IndividueelAanbod</a>
        <ul>
            <li><a href="#individueelaanbod-class">Class</a></li>
            <li><a href="#individueelaanbod-properties">Properties</a></li>
        </ul>
    </li>
    <li><a href="#groepsaanbod">GroepsAanbod</a>
        <ul>
            <li><a href="#groepsaanbod-class">Class</a></li>
            <li><a href="#groepsaanbod-properties">Properties</a>
                <ul>
                    <li>minAantalDeelnemers</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#activiteit">Activiteit</a>
        <ul>
            <li><a href="#activiteit-class">Class</a></li>
            <li><a href="#activiteit-properties">Properties</a>
                <ul>
                    <li>aanbod</li>
                    <li>aantal aanmeldingen</li>
                    <li>aantal inschrijvingen</li>
                    <li>annulatie reden</li>
                    <li>infrastructuur</li>
                    <li>naam</li>
                    <li>status</li>
                    <li>subactiviteit</li>
                    <li>superactiviteit</li>
                    <li>tijdschema</li>
                    <li>vervangen door</li>
                    <li>vervangt</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#sessie">Sessie (subclass of Activiteit)</a>
        <ul>
            <li><a href="#sessie-class">Class</a></li>
            <li><a href="#sessie-properties">Properties</a></li>
        </ul>
    </li>
    <li><a href="#sessiereeks">Sessiereeks (subclass of Activiteit)</a>
        <ul>
            <li><a href="#sessiereeks-class">Class</a></li>
            <li><a href="#sessiereeks-properties">Properties</a></li>
        </ul>
    </li>
    <li><a href="#doelgroep">Doelgroep</a>
        <ul>
            <li><a href="#doelgroep-class">Class</a></li>
            <li><a href="#doelgroep-properties">Properties</a>
                <ul>
                    <li>kenmerk</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#doelgroepkenmerk">DoelgroepKenmerk</a>
        <ul>
            <li><a href="#doelgroepkenmerk-class">Class</a></li>
            <li><a href="#doelgroepkenmerk-properties">Properties</a>
                <ul>
                    <li>deel van</li>
                    <li>kenmerktype</li>
                    <li>waarde</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#gebruiktevte">GebruikteVTE</a>
        <ul>
            <li><a href="#gebruiktevte-class">Class</a></li>
            <li><a href="#gebruiktevte-properties">Properties</a>
                <ul>
                    <li>aantal</li>
                    <li>vteType</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#financiering">Financiering</a>
        <ul>
            <li><a href="#financiering-class">Class</a></li>
            <li><a href="#financiering-properties">Properties</a>
                <ul>
                    <li>bedrag</li>
                    <li>financieringstype</li>
                    <li>gefinancierd door</li>
                    <li>karakter</li>
                    <li>uitbetalingsmoment start</li>
                    <li>uitbetalingsmoment einde</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#financieringsbron">Financieringsbron</a>
        <ul>
            <li><a href="#financieringsbron-class">Class</a></li>
            <li><a href="#financieringsbron-properties">Properties</a>
                <ul>
                    <li>beleidsdomein</li>
                    <li>financiert</li>
                    <li>niveau</li>
                </ul>
            </li>
        </ul>
    </li>
</ul>

<h1>OSLO zaalreservaties</h1>

<div id="publiekeorganisatie">
    <h2>PubliekeOrganisatie</h2>
    <h3>Class</h3>
    <p>This is repurposed from OSLO-Organisatie.</p>
    <h4>Properties</h4>
    <ul>
        <li>contactinfo</li>
        <li>voorkeursnaam</li>
        <li>werkingsgebied</li>
    </ul>
</div>

<h2>Infrastructuurreservatiedienst</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-PubliekeDienstverlening.</p>
<ul>
    <li>Properties
        <ul>
            <li>alternatieveNaam</li>
            <li>beschrijving</li>
            <li>contactinfo</li>
            <li>naam</li>
            <li>ruimtelijkeDekking</li>
            <li>status</li>
            <li>taal</li>
            <li>trefwoord</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Infrastructuurreservatie</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Output and OSLO-Reservatie.</p>
<ul>
    <li>Properties
        <ul>
            <li>gerserveerdDoor</li>
            <li>gereserveerdVoor</li>
            <li>periode</li>
            <li>buffer</li>
            <li>status</li>
        </ul>
        <p>There was a specific request to add a buffer period, meaning a period during which the venue cannot be reserved, for example, to allow for cleaning. This attribute did not previously exist in OSLO and was therefore added.</p>
    </li>
</ul>

<h2>Infrastrucuur</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>bereikbaarheid</li>
            <li>berschikbaarheid</li>
            <li>beschrijving</li>
            <li>capaciteit</li>
            <li>contactpersoon</li>
            <li>dimensie</li>
            <li>eigenaar</li>
            <li>faciliteit</li>
            <li>gebruik</li>
            <li>locatie</li>
            <li>naam</li>
            <li>openingsuren</li>
            <li>openstelling</li>
            <li>toegankelijkheid</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Binnenruimte</h2>
<h3>(sub)class</h3>
<p>To reserve a hall, it is necessary to secure a suitable space. The spaces can be adapted and repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
            <li>verbondenAan</li>
            <p>A 'Binnenruimte’ can be linked to an infrastructure.</p>
        </ul>
    </li>
</ul>

<h2>Buitenruimte</h2>
<h3>Subclass</h3>
<p>To reserve a hall, it is necessary to secure a suitable space. The spaces can be adapted and repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
            <li>verbondenAan</li>
            <p>A ‘Buitenruimte’ can be linked to an infrastructure.</p>
        </ul>
    </li>
</ul>

<h2>Document</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Agent</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Faciliteit</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>beschrijving</li>
            <li>document</li>
            <li>gebruiker</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Gebruik</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>exclusiviteit</li>
            <li>gebruiker</li>
            <li>periode</li>
            <li>voorwaarde</li>
        </ul>
    </li>
</ul>

<h2>Activiteit</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Cultuurparticipatie.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Eigenaarschap</h2>
<h3>Class</h3>
<p>The stakeholders wish to identify the owner of the infrastructure, as this may vary. This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>eigenaar</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Criterion</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Consent.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Plaats</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties
        <ul>
            <li>geometrie</li>
            <li>plaatsnaam</li>
        </ul>
    </li>
</ul>

<h2>PubliekeOrganisatie</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Organisatie.</p>
<ul>
    <li>Properties
        <ul>
            <li>contactinfo</li>
            <li>voorkeursnaam</li>
            <li>werkingsgebied</li>
        </ul>
    </li>
</ul>

<h2>Infrastructuurreservatiedienst</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-PubliekeDienstverlening.</p>
<ul>
    <li>Properties
        <ul>
            <li>alternatieveNaam</li>
            <li>beschrijving</li>
            <li>contactinfo</li>
            <li>naam</li>
            <li>ruimtelijkeDekking</li>
            <li>status</li>
            <li>taal</li>
            <li>trefwoord</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Infrastructuurreservatie</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Output and OSLO-Reservatie.</p>
<ul>
    <li>Properties
        <ul>
            <li>gerserveerdDoor</li>
            <li>gereserveerdVoor</li>
            <li>periode</li>
            <li>buffer</li>
            <li>status</li>
        </ul>
        <p>There was a specific request to add a buffer period, meaning a period during which the venue cannot be reserved, for example, to allow for cleaning. This attribute did not previously exist in OSLO and was therefore added.</p>
    </li>
</ul>

<h2>Infrastrucuur</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>bereikbaarheid</li>
            <li>berschikbaarheid</li>
            <li>beschrijving</li>
            <li>capaciteit</li>
            <li>contactpersoon</li>
            <li>dimensie</li>
            <li>eigenaar</li>
            <li>faciliteit</li>
            <li>gebruik</li>
            <li>locatie</li>
            <li>naam</li>
            <li>openingsuren</li>
            <li>openstelling</li>
            <li>toegankelijkheid</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Binnenruimte</h2>
<h3>Subclass</h3>
<p>To reserve a hall, it is necessary to secure a suitable space. The spaces can be adapted and repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
            <li>verbondenAan</li>
            <p>A 'Binnenruimte’ can be linked to an infrastructure.</p>
        </ul>
    </li>
</ul>

<h2>Buitenruimte</h2>
<h3>Subclass</h3>
<p>To reserve a hall, it is necessary to secure a suitable space. The spaces can be adapted and repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
            <li>verbondenAan</li>
            <p>A ‘Buitenruimte’ can be linked to an infrastructure.</p>
        </ul>
    </li>
</ul>

<h2>Document</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Agent</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Faciliteit</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>beschrijving</li>
            <li>document</li>
            <li>gebruiker</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Gebruik</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>exclusiviteit</li>
            <li>gebruiker</li>
            <li>periode</li>
            <li>voorwaarde</li>
        </ul>
    </li>
</ul>

<h2>Activiteit</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Cultuurparticipatie.</p>
<ul>
    <li>Properties
        <ul>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Eigenaarschap</h2>
<h3>Class</h3>
<p>The stakeholders wish to identify the owner of the infrastructure, as this may vary. This is repurposed from OSLO-CultuurEnJeugdinfrastructuur.</p>
<ul>
    <li>Properties
        <ul>
            <li>eigenaar</li>
            <li>type</li>
        </ul>
    </li>
</ul>

<h2>Criterion</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Consent.</p>
<ul>
    <li>Properties: Doesn't have own properties.</li>
</ul>

<h2>Plaats</h2>
<h3>Class</h3>
<p>This is repurposed from OSLO-Generiek.</p>
<ul>
    <li>Properties
        <ul>
            <li>geometrie</li>
            <li>plaatsnaam</li>
        </ul>
    </li>
</ul>
