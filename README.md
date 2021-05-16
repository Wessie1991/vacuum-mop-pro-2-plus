# vacuum-mop-pro-2-plus (vacuum.p2041o)
this is intergration for  vacuum-mop-pro-2-plus divice name dreame.vacuum.p2041o
 https://nl.aliexpress.com/item/1005001592602003.html?spm=a2g0s.9042311.0.0.2f4d4c4dysaCL4
 

voor alle overige moddel kan je hier kijken: http://miot-spec.org/miot-spec-v2/instances?status=all


list of the attribues : https://miot-spec.org/miot-spec-v2/instance?type=urn:miot-spec-v2:device:vacuum:0000A006:dreame-p2041o:1

this intergration is fo : Xiaomi Mi Robot Vacuüm Mop 2 Pro +
 
add this to the Configuration.yaml

vacuum:
 - platform: xiaomi_vacuum
   host: <local ip of the vacuum>
   token: <api Token>
   name: <naam for the vacuum>

for token look here : https://www.home-assistant.io/integrations/xiaomi_miio/ 


create folders inside of the configfolder 
- config:
  - custom_components
    - xiaomi_vacuum
      - paste here all your files from the github 


it's is a fast and ugly project because i dindt find a competibel intergration for my vacuum  robot 
