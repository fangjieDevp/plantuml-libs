# MaterialsLocationSearching
```text
elements/materials/Device/MaterialsLocationSearching
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsLocationSearching icon](../../../icons/materials/Device/MaterialsLocationSearching.png) | ![MaterialsLocationSearching element](MaterialsLocationSearching.element.png) | ![MaterialsLocationSearching card](MaterialsLocationSearching.card.png) |
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

' loads the MaterialsLocationSearching element
include('elements/materials/Device/MaterialsLocationSearching')
MaterialsLocationSearching('element', 'Location Searching', 'an optional tech field')
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

' loads the MaterialsLocationSearching element
include('elements/materials/Device/MaterialsLocationSearching')
MaterialsLocationSearching('element', 'Location Searching', 'an optional tech field')
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

' loads the MaterialsLocationSearching card
include('elements/materials/Device/MaterialsLocationSearching')
MaterialsLocationSearchingCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsLocationSearching card
include('elements/materials/Device/MaterialsLocationSearching')
MaterialsLocationSearchingCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
