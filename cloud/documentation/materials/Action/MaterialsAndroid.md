# MaterialsAndroid
```text
elements/materials/Action/MaterialsAndroid
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsAndroid icon](../../../icons/materials/Action/MaterialsAndroid.png) | ![MaterialsAndroid element](MaterialsAndroid.element.png) | ![MaterialsAndroid card](MaterialsAndroid.card.png) |
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

' loads the MaterialsAndroid element
include('elements/materials/Action/MaterialsAndroid')
MaterialsAndroid('element', 'Android', 'an optional tech field')
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

' loads the MaterialsAndroid element
include('elements/materials/Action/MaterialsAndroid')
MaterialsAndroid('element', 'Android', 'an optional tech field')
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

' loads the MaterialsAndroid card
include('elements/materials/Action/MaterialsAndroid')
MaterialsAndroidCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsAndroid card
include('elements/materials/Action/MaterialsAndroid')
MaterialsAndroidCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
