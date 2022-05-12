# Android-Architecture

rest api
retrofit 2
postman
coroutines
 live data
navigation
data binding
room

## MVVM (Model–view–viewmodel) 
Model–view–viewmodel is a software architectural pattern that facilitates the separation of the development of the graphical user interface – be it via a markup language or GUI code


<img src="https://user-images.githubusercontent.com/91980956/154803061-1912740b-72d1-4eda-80cb-410552bf901c.png" width="500" height="500" />

### MVVM Android-Architecture
<img src="https://user-images.githubusercontent.com/91980956/154803223-9166b476-e711-4dfe-a45b-f6ececa1d0c7.png" width="700" height="500" />

## MVVM Components (impo link)
https://medium.com/swlh/deep-dive-into-mvvm-architecture-components-bd1e3dfdb930
<img src="https://user-images.githubusercontent.com/91980956/158063609-a1e57698-3399-4009-9f17-fbe1a1cdf420.png" width="700" height="500" />

## View Binding
difference between from find view by id (no need to find any id) <br/>
null safety ( when to find a view that doesnot exixts it will cought by null safety) <br/>
Type safety (jodi kono button e wrong id diye deoa hoi and onnek gula button ase run kore check korte onnek time lage jai type safety run korar somoi ei error dhore fele) <br/>

## Data Binding
Data Binding Library Part of Android Jetpack. The Data Binding Library is a support library that allows you to bind UI components in your layouts to data sources in your app using a declarative format rather than programmatically. (mane xml er modhei kaj shes hoiye jabe layout er extra vabe activity te code kora lagbe na)
```diff
id 'kotlin-kapt
 buildFeatures{
        dataBinding true
    }

```

## View Model
ViewModel Overview Part of Android Jetpack. The ViewModel class is designed to store and manage UI-related data in a lifecycle conscious way. The ViewModel class allows data to survive configuration changes such as screen rotations. <br/>
mane m=ami jodi kono data store kori and amr phone er kono setting change kori or phone rotate kori tahole oi old data ta remove hoiye jabe and data notun kotre create kora suru hobe. as amdr ei data ta main activity te thake tai remove hoiye jai. amra jdi alada vabe class create kore oi data ta oi class e store kori and main activity te call kori tahole kaj shes.. eitakei bole view model

```diff
//dependency
def lifecycle_version = "2.3.1"
    //def lifecycle_version = "2.4.0-alpha02"

```




## MVP (Model–view–presenter)
Model–view–presenter is a derivation of the model–view–controller architectural pattern, and is used mostly for building user interfaces. In MVP, the presenter assumes the functionality of the "middle-man". In MVP, all presentation logic is pushed to the presenter.

<img src="https://user-images.githubusercontent.com/91980956/154803398-a05e225b-884f-415a-b514-b8d39a7ae7c9.png" width="500" height="500" />

### MVP Android-Architecture
<img src="https://user-images.githubusercontent.com/91980956/154803449-0ca76da3-a8ff-43b6-8575-aaa791ec4c97.png" width="700" height="500" />

## MVC (Model–view–controller)
Model–view–controller is a software design pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements.

<img src="https://user-images.githubusercontent.com/91980956/154803517-75013f0d-5219-4411-b948-01db847583c5.png" width="500" height="500" />

### MVC Android-Architecture
<img src="https://user-images.githubusercontent.com/91980956/154803566-d3798526-f99e-4039-93a3-24e47898019d.png" width="700" height="500" />




