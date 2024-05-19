


## MVVM
### Movel-View-Viewmodel

#### Model
Handles data, external apis, etc.
This would be most similar to a Controller that you are already familiar with

#### ViewModel
This is the bridge between the model and the view. All state in general is stored within the ViewModel. The view model passes data from the model to the view and vice versa

#### View
This is where the user screen is drawn. The UI is displayed here from the model

The view forwards user actions to the ViewModel

#### Repository
A repository is the bridge between each of these three major components


### Package Structure
- App (Core Components)
	- Data
		- Repository
	- Presentation
- Feature (Specific Components)
	- Data
