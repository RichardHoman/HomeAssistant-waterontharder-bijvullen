# HomeAssistant-waterontharder-bijvullen

ALL FILES ARE IN DUTCH - FROM THIS POINT ON, SO WILL THE README BE

Met deze automatisering en dashboardkaart kan eenvoudig worden ingesteld en bijgehouden wanneer een waterontharder moet worden bijgevuld met zout.

Voor het werkend maken van de automatisering is een watermeter vereist. In deze versie is de naam van de watermeter-sensor alsvolgt:
sensor.watermeter_total_water_usage

Verder zijn een drietal helpers nodig. Een helper om bij te houden wat de watermeterstand was ten tijde van de laatste vulling met zout en een helper waarin aangegeven wordt hoeveel m3 water verbruikt moet zijn voor de waterontharder weer moet worden bijgevuld. De laatste is de knop die vanuit het dashboard wordt ingedrukt. Deze helpers hebben in deze versie de volgende namen:
input_number.waterverbruik_tussen_bijvullen_ontharder (in kuub, de scripts rekenen dit om naar liters)
input_number.meterstand_water_bij_waterontharder_gevuld
input_button.waterontharder_bijgevuld
