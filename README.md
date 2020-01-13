# Chocolatey 

[![Build status](https://ci.appveyor.com/api/projects/status/sli76aallhvlthm1?svg=true)](https://ci.appveyor.com/project/paulalves/choco-install)

Este repositório contém um script para execução do chocolatey com as aplicações mais comuns que uso no dia a dia, onde você pode instalar todos os aplicativos em segundo plano, sem intervenção um a um.

Você deve rodar o powershell como administrador e executar o seguinte comando: 

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/luiscrjr/ChocoIsPeaceOfCake/master/Install.ps1'))
```