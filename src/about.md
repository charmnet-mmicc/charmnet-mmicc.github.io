## About CHARMNET

Our Center is supported by the the Advanced Scientific Computing Research program of the U.S. Department of Energy.

----

## Our Team 

{% set members = ['A_Christlieb', 'L_Chacon', 'S_Becker', 'D_Bortz', 'J_Burby', 'Y_Cheng', 'Y_Choi', 
'S_Gottlieb', 'C_Hauck', 'T_Haut', 'J_Hittinger', 'J_Hu', 'J_Jakeman', 'H_Lei','D_Messenger', 
'B_Oshea', 'J_Qiu', 'L_Ricketson', 'S_Schotthoefer', 'Q_Tang', 'W_Taitano', 'P_Tranquilli', 'T_Wildey'] %}

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

