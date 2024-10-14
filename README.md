# Apuntes
Apuntes de 1DAM
 Get-ChildItem -path "C:\datos\*" | Foreach {
$Files = Get-ChildItem $_.FullName -Recurse -File
$Size = '{0:N2}' -f (( $Files | Measure-Object -Property Length -Sum).Sum /1MB)
[PSCustomObject]@{Profile = $_.FullName ; TotalObjects = "$($Files.Count)" ; SizeMB = $Size}
}
