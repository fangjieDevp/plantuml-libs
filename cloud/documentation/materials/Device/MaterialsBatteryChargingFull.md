# MaterialsBatteryChargingFull
```text
elements/materials/Device/MaterialsBatteryChargingFull
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsBatteryChargingFull icon](../../../icons/materials/Device/MaterialsBatteryChargingFull.png) | ![MaterialsBatteryChargingFull element](MaterialsBatteryChargingFull.element.png) | ![MaterialsBatteryChargingFull card](MaterialsBatteryChargingFull.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBatteryChargingFull element
include('elements/materials/Device/MaterialsBatteryChargingFull')
MaterialsBatteryChargingFull('element', 'Battery Charging Full', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBatteryChargingFull element
include('elements/materials/Device/MaterialsBatteryChargingFull')
MaterialsBatteryChargingFull('element', 'Battery Charging Full', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBatteryChargingFull card
include('elements/materials/Device/MaterialsBatteryChargingFull')
MaterialsBatteryChargingFullCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBatteryChargingFull card
include('elements/materials/Device/MaterialsBatteryChargingFull')
MaterialsBatteryChargingFullCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
