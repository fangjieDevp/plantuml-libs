# MaterialsPhoneLocked
```text
elements/materials/Notification/MaterialsPhoneLocked
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsPhoneLocked icon](../../../icons/materials/Notification/MaterialsPhoneLocked.png) | ![MaterialsPhoneLocked element](MaterialsPhoneLocked.element.png) | ![MaterialsPhoneLocked card](MaterialsPhoneLocked.card.png) |
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

' loads the MaterialsPhoneLocked element
include('elements/materials/Notification/MaterialsPhoneLocked')
MaterialsPhoneLocked('element', 'Phone Locked', 'an optional tech field')
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

' loads the MaterialsPhoneLocked element
include('elements/materials/Notification/MaterialsPhoneLocked')
MaterialsPhoneLocked('element', 'Phone Locked', 'an optional tech field')
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

' loads the MaterialsPhoneLocked card
include('elements/materials/Notification/MaterialsPhoneLocked')
MaterialsPhoneLockedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsPhoneLocked card
include('elements/materials/Notification/MaterialsPhoneLocked')
MaterialsPhoneLockedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
