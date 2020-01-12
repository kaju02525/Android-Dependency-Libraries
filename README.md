# Android-Dependency-Libraries for Karun Kumar

# Usage
### 1.Scratch And Win:
implementation 'com.github.kaju02525:ScratchWinLibrary:0.1.0'

### 2.Spin And Wheel:
implementation 'com.github.kaju02525:WindsSpinWheel:0.1.0'

### 3.ImagePicker With Crop:
implementation 'com.github.kaju02525:ImagePickerWithCrop:0.1.0'

### 4.Smart LocationGPS With Current:  latitude and longitude
implementation 'com.github.kaju02525:SmartLocationGPS:0.0.1'


maven { url 'https://jitpack.io' } 

implementation 'androidx.legacy:legacy-support-v4:1.0.0'
implementation 'androidx.recyclerview:recyclerview:1.1.0-alpha02'
implementation 'com.google.android.material:material:1.0.0'
implementation 'androidx.cardview:cardview:1.0.0'

implementation 'com.synnapps:carouselview:0.1.5'
implementation 'com.amitshekhar.android:android-networking:1.0.2'
implementation 'com.squareup.picasso:picasso:2.3.2'
implementation 'de.hdodenhof:circleimageview:2.2.0'
implementation 'com.thoughtbot:expandablerecyclerview:1.3'
implementation 'com.robertlevonyan.view:MaterialChipView:1.2.5'

implementation 'com.github.tcking:giraffeplayer2:0.1.19-lazyLoad'
implementation 'com.github.faruktoptas:FancyShowCaseView:1.1.0'
implementation 'com.github.sundeepk:compact-calendar-view:3.0.0'
implementation 'com.github.cdflynn:turn-layout-manager:v1.2'
implementation 'com.github.takusemba:multisnaprecyclerview:1.3.3'
implementation 'com.ramotion.cardslider:card-slider:0.3.0'
implementation 'com.ramotion.circlemenu:circle-menu:0.3.2'

implementation 'com.github.halilozercan:BetterVideoPlayer:1.2.alpha1'
implementation 'com.github.ybq:Android-SpinKit:1.1.0'
implementation 'com.budiyev.android:circular-progress-bar:1.2.2'
implementation 'com.github.GrenderG:Toasty:1.3.1'

implementation 'fm.jiecao:jiecaovideoplayer:5.7'
implementation 'com.github.cdflynn:turn-layout-manager:v1.2'
implementation 'io.github.yavski:fab-speed-dial:1.0.6'
implementation 'com.github.yalantis:ucrop:2.2.2'

//animation library
implementation 'com.daimajia.easing:library:2.0@aar'
implementation 'com.daimajia.androidanimations:library:2.3@aar'
implementation 'com.facebook.android:account-kit-sdk:4.37.0'
implementation 'com.google.android.gms:play-services-auth:16.0.1'


def okhttp_version = '3.8.1'
def retrofit_version = '2.2.0'
def rxjava_version = '2.1.7'
def androidArchitectureVersion = "1.1.0"

implementation 'androidx.appcompat:appcompat:1.1.0'
implementation 'androidx.core:core-ktx:1.1.0'

//json
implementation 'com.google.code.gson:gson:2.8.5'

// Networking
implementation "com.squareup.retrofit2:retrofit:$retrofit_version"
implementation "com.squareup.retrofit2:converter-gson:$retrofit_version"
implementation "com.squareup.retrofit2:adapter-rxjava2:$retrofit_version"
implementation "com.squareup.okhttp3:okhttp:$okhttp_version"
implementation "com.squareup.okhttp3:logging-interceptor:$okhttp_version"

// ViewModel and LiveData
implementation "android.arch.lifecycle:extensions:$androidArchitectureVersion"
annotationProcessor "android.arch.lifecycle:compiler:$androidArchitectureVersion"

// Rx
implementation "io.reactivex.rxjava2:rxjava:$rxjava_version"
implementation 'io.reactivex.rxjava2:rxandroid:2.1.1'

def koin_version = '2.0.1'
implementation "org.koin:koin-android:$koin_version"
implementation "org.koin:koin-android-viewmodel:$koin_version"

// Dimention
implementation 'com.intuit.sdp:sdp-android:1.0.6'
implementation 'com.intuit.ssp:ssp-android:1.0.6'

//room
implementation "android.arch.persistence.room:runtime:1.1.1"
annotationProcessor "android.arch.persistence.room:compiler:1.1.1"
annotationProcessor "android.arch.lifecycle:compiler:1.1.1"
kapt "android.arch.persistence.room:compiler:1.1.1"
kapt "android.arch.lifecycle:compiler:1.1.1"
implementation "android.arch.lifecycle:extensions:1.1.1"



