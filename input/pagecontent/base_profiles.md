### FHIR profile layers

As part of a layered approach to profiling, these profiles represent a flexible base defining common concepts without constraints. Base profiles are about how concepts are represented and are useable in any use case or scenario.

<div>
  <p> </p>
  <figure>
    <img src="fhir-layers-derivation-web.png" alt="FHIR profile layers" width="65%"/>
    <figcaption>
        Fig. 1 – Profile layers
    </figcaption>
  </figure>
  <p> </p>
</div>

### Rules of thumb

<p><strong>Base profiles are permissive</strong></p>
They describe local concepts; leave "mandatory" to the use case, otherwise every use case inherits constraints it doesn't need.

<p><strong>Use base profiles</strong></p>
Specialize/constrain the base profile, so national identifiers and extensions are reused rather than reinvented.

### Relationship to European profiles

Managing many different profiles and their relationships is an area under development. There are extensions to mark relationships between profiles and more options coming in the future.
At the moment, the Swedish base profiles do not derive from the European profiles.

<div>
  <p> </p>
  <figure>
    <img src="fhir-eu-relation-web.png" alt="European profiles relationship" width="65%"/>
    <figcaption>
        Fig. 2 – Base and European profiles
    </figcaption>
  </figure>
  <p> </p>
</div>

### Where are the core profiles?

Sweden is historically and legally decentralized when it comes to the provision of healthcare. At present, HL7 Sweden publishes base profiles but hands over the responsibility for more constrained profiles to organizations closer to the implementation.

HL7 affiliates commonly publish base and core profiles, where core profiles build on the base profiles and introduce general restrictions and obligations. As the work done by HL7 Sweden is driven by the needs and participation of the community, core profiles will be considered when there is enough national alignment and interest.
