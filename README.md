# UsefulDependencies

## Dagger
https://github.com/google/dagger

    api 'com.google.dagger:dagger:2.x'
    annotationProcessor 'com.google.dagger:dagger-compiler:2.x'
Dagger.android

    api 'com.google.dagger:dagger-android:2.x'
    api 'com.google.dagger:dagger-android-support:2.x' // if you use the support libraries
    annotationProcessor 'com.google.dagger:dagger-android-processor:2.x' 
    

## Design

    implementation 'com.android.support:design:28.0.0'
    implementation 'com.nostra13.universalimageloader:universal-image-loader:1.9.5'
    
## Lifecycle
https://developer.android.com/jetpack/androidx/releases/lifecycle#java

ViewModel

    implementation "androidx.lifecycle:lifecycle-viewmodel:$lifecycle_version"
LiveData

    implementation "androidx.lifecycle:lifecycle-livedata:$lifecycle_version"

## Retrofit 
https://github.com/square/retrofit

    implementation 'com.squareup.retrofit2:retrofit:2.5.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.5.0'
    
## Room
https://developer.android.com/jetpack/androidx/releases/room
    
    def room_version = "2.2.5"

    implementation "androidx.room:room-runtime:$room_version"   
    annotationProcessor "androidx.room:room-compiler:$room_version"
RxJava support
    
    implementation "androidx.room:room-rxjava2:$room_version"

## RxJava, RxAndroid, RxBinding 

    implementation "io.reactivex.rxjava3:rxjava:3.0.2"
    implementation 'io.reactivex.rxjava3:rxandroid:3.0.0'
    implementation 'com.jakewharton.rxbinding3:rxbinding:3.1.0'
    
* RxAndroid: <a href='http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22io.reactivex.rxjava3%22%20a%3A%22rxandroid%22'><img src='http://img.shields.io/maven-central/v/io.reactivex.rxjava3/rxandroid.svg'></a>
* RxJava: <a href='http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22io.reactivex.rxjava3%22%20a%3A%22rxjava%22'><img src='http://img.shields.io/maven-central/v/io.reactivex.rxjava3/rxjava.svg'></a>

* RxBinding: https://github.com/JakeWharton/RxBinding
    



    
