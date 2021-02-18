# telemetry-reference-dashboard

# Objectives
A centralized reference telemetry dashboard json export artifacts.

Reference dashboard design json permission is different from permission control of live datadog dashboards.

# How to organize dashboard JSON artifacts

- Dashboards JSON files organized by product.
- Dashboard JSON file should have meaningful name.
- Dashboard JSON artifact must have proper version control and proper change review process.
- Dashboard json can be imported to datadog and as starting point for other team to reference or futhre enhancement/customization.


#A possible flow 

Could be something like this:

    1 Q2- DL published a new reference dashboard and storied in the repo 
    2 DL provide clear description on the purpose and other information in this repo 
    including the dependencies such as which build including those additional metrics needed for the dashboard.

    3.1 CloudOp team can review and clone this repo, but can't change original reference dd json
    3.2 CloudOp team imported to DataDog, plays with it, then enhancement and tweak it.
    3.3 CloudOp team comes with a new DD and set permission for proper CloudOp team.

or

    4.1 CS team can review and clone this repo, but can't change reference dd json
    4.2  CS team imported to DataDog, plays with it, then enhancement and tweak it.
    4.3 CS team comes with a new DD and set permission for proper CS team.


# To be clear the repo is not real.

Just to demonstrate what is needed and no real dashboards!!!! 