# MaterialsDevicesOther
```text
elements/materials/Hardware/MaterialsDevicesOther
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsDevicesOther icon](../../../icons/materials/Hardware/MaterialsDevicesOther.png) | ![MaterialsDevicesOther element](MaterialsDevicesOther.element.png) | ![MaterialsDevicesOther card](MaterialsDevicesOther.card.png) |
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

' loads the MaterialsDevicesOther element
include('elements/materials/Hardware/MaterialsDevicesOther')
MaterialsDevicesOther('element', 'Devices Other', 'an optional tech field')
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

' loads the MaterialsDevicesOther element
include('elements/materials/Hardware/MaterialsDevicesOther')
MaterialsDevicesOther('element', 'Devices Other', 'an optional tech field')
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

' loads the MaterialsDevicesOther card
include('elements/materials/Hardware/MaterialsDevicesOther')
MaterialsDevicesOtherCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsDevicesOther card
include('elements/materials/Hardware/MaterialsDevicesOther')
MaterialsDevicesOtherCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
