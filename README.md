# VSCode Haskutil
[![Build Status](https://travis-ci.org/EduardSergeev/vscode-haskutil.svg?branch=master)](https://travis-ci.org/EduardSergeev/vscode-haskutil)

'QuickFix' actions for Haskell editor  
Available at [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=Edka.haskutil)

## Installation
This extension uses diagnostics (errors) from `PROBLEM` window which is populated by other Haskell extension such as [Simple GHC](https://marketplace.visualstudio.com/items?itemName=dramforever.vscode-ghc-simple) or [Haskero](https://marketplace.visualstudio.com/items?itemName=Vans.haskero). Please install either of them along with this extension.

## Features

1. Add missing import  
![Add missing import](/gifs/AddImport_sm.gif "Add missing import")

2. Add LANGUAGE extension  
![Add extension](/gifs/AddExtension_sm.gif "Add extension")

## Dependencies

 * Automatic dependency (auto install) [hoogle-vscode](https://marketplace.visualstudio.com/items?itemName=jcanero.hoogle-vscode)
