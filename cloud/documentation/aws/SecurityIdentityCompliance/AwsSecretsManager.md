# AwsSecretsManager
```text
elements/aws/SecurityIdentityCompliance/AwsSecretsManager
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsSecretsManager icon](../../../icons/aws/SecurityIdentityCompliance/AwsSecretsManager.png) | ![AwsSecretsManager element](AwsSecretsManager.element.png) | ![AwsSecretsManager card](AwsSecretsManager.card.png) |
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
include('styles/aws')

' loads the AwsSecretsManager element
include('elements/aws/SecurityIdentityCompliance/AwsSecretsManager')
AwsSecretsManager('element', 'Secrets Manager', 'an optional tech field')
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
include('styles/aws')

' loads the AwsSecretsManager element
include('elements/aws/SecurityIdentityCompliance/AwsSecretsManager')
AwsSecretsManager('element', 'Secrets Manager', 'an optional tech field')
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
include('styles/aws')

' loads the AwsSecretsManager card
include('elements/aws/SecurityIdentityCompliance/AwsSecretsManager')
AwsSecretsManagerCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsSecretsManager card
include('elements/aws/SecurityIdentityCompliance/AwsSecretsManager')
AwsSecretsManagerCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
