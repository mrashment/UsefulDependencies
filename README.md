# UsefulDependencies

## Coroutines
https://github.com/Kotlin/kotlinx.coroutines

    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.3.7'
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.7'
    
## Dagger
https://github.com/google/dagger

    def dagger_version = "2.27"
    
    implementation "com.google.dagger:dagger:$dagger_version"
    annotationProcessor "com.google.dagger:dagger-compiler:$dagger_version"
    
    implementation "com.google.dagger:dagger-android:$dagger_version"
    implementation "com.google.dagger:dagger-android-support:$dagger_version"
    annotationProcessor "com.google.dagger:dagger-android-processor:$dagger_version"

    

## Design

    implementation 'com.google.android.material:material:1.1.0'
    implementation 'com.nostra13.universalimageloader:universal-image-loader:1.9.5'
    
## Firebase

    implementation 'com.google.firebase:firebase-core:17.4.0'
    implementation 'com.google.firebase:firebase-auth:19.3.1'
    implementation 'com.google.firebase:firebase-database:19.3.0'
    implementation 'com.google.firebase:firebase-storage:19.1.1'
    implementation 'com.google.firebase:firebase-analytics:17.4.0'
    
## Glide

    implementation 'com.github.bumptech.glide:glide:4.11.0'
    annotationProcessor 'com.github.bumptech.glide:compiler:4.11.0'
    
## Google
https://github.com/google/gson

    implementation 'com.google.android.gms:play-services-auth:18.0.0'
    
## Gson

    implementation 'com.google.code.gson:gson:2.8.6'
    
## Lifecycle
https://developer.android.com/jetpack/androidx/releases/lifecycle#java

ViewModel

    implementation "androidx.lifecycle:lifecycle-viewmodel:$lifecycle_version"
LiveData

    implementation "androidx.lifecycle:lifecycle-livedata:$lifecycle_version"
    
## Picasso
https://github.com/square/picasso

implementation 'com.squareup.picasso:picasso:2.71828'

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
    



    
