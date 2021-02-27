# [WARGAME] Underthewire - Century

## Century1

Joining their slack channel
>century1

## Century2

Find the PS buildversion  
`$PSversionTable or  $PSversionTable.Buildversion`

>10.0.14393.3866

## Century3

Find the cmdlet for wget → `Invoke-webrequest` add this with file name present in desktop.  
`dir,ls,get-childitem`  
> 443

`invoke-webrequest`  
In PS-`curl,wget,invoke-webrequest`

## Century4

`Get-ChildItem -file | Measure-Object`
> 123

## Century5

`Get-ChildItem -path 'C:\users\century4\desktop\Can You Open Me'`  

>61580

## Century6

`Get-ADDomain / hostname`

>Name : underthewire
> underthewire3347

## Century7

`Get-ChildItem -directory| Measure-Object`  

>197

## Centurty8

`Get-ChildItem -path C:\users\century7 -Filter Readme.txt -Recurse`  

>Directory: C:\users\century7\Downloads  

`Get-Content .\Readme.txt`
> 7points

## Century9

`$A = $(foreach ($line in Get-Content unique.txt) {$line}) | sort | Get-Unique`  

`$A.count`  

>696

## Century10

`$A = $(foreach ($line in Get-Content Word_File.txt) {$line.split(" ")})`  

`$A[160]` as it starts with 0

> pierid

## Century11

`$A = $(foreach ($line in (Get-WmiObject -Class 'win32_service' | Where-Object {$_.Name -eq 'wuauserv'} | Select-Object -ExpandProperty Description )) {$line.split(" ")})`  

`$A[7]`  
`$A[9]`

> windowsupdates110

## Century12

`Get-ChildItem -Recurse -Hidden`  

>Directory: C:\users\century11\Downloads  
>Secret_sauce

## Century13

`Get-ADComputer -Filter {Name -Eq "UTW"} -Properties description`  
> i_authenticate_things

## Century14

`$A = $(foreach ($line in Get-Content countmywords ){$line.split(" ")})`  

`$A.count`
> 755

## Century15

`-split (Get-Content countpolos | Out-String) | Where-Object { $_ -eq "polo" } | Measure-Object`
> 153

### The End
