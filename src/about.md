## About CHARMNET

We are a Focused Investigatory Centers (FICs) supported by the Predictive Science Academic Alliance Program (PSAAP), managed by the NNSA Office of Advanced Simulation and Computing (ASC).

----

## Our Team 

{% set members = ['A_Christlieb', 'Q_Tang' ] %}

{% for member in members %}
<div class="row">
    <div class="col-md-2">
        <img src="../bios/{{ member }}.jpg" alt="Missing picture" width="100%">
    </div>
    <div class="col-md-10">
        <br><p>
        {% set bio = "/bios/" + member + ".html" %}
            {% include bio %}
        </p>
    </div>
</div>
{% endfor %}

