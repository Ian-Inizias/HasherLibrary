# HasherLibrary

### Instalation
#### Package Manager
Install-Package HasherLibrary -Version 1.0.1
#### .NET CLI
dotnet add package HasherLibrary --version 1.0.1
#### Package Reference
< PackageReference Include="HasherLibrary" Version="1.0.1" />
#### paket cli
paket add HasherLibrary --version 1.0.1

### Usage
#### HasherV3
<b>HasherV3.GetRandomKeyHashPair()</b>  
Gets a random password and hash pair

<b>HasherV3.GenerateIdentityV3Hash(password)</b>  
Given a password generates the identity hash


#### Password
<b>Password.GeneratePassword(includeLowercase, includeUppercase, includeNumeric, includeSpecial, includeSpaces, lengthOfPassword)</b>  
Given the choosen parameters generates a valid random password
