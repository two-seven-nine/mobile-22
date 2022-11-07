# Preparing for Mobile Interview

## Android framework
  - [ ] ART
  - [ ] ART vs Dalvik
  - [ ] App profiles
  - [ ] Garbage collection

## Development

### Kotlin (https://gist.github.com/paulfranco/4453383cc6df064d03087ce7aa5a0c8c)
  - [ ] Nothing type
  - [ ] reified
  - [ ] inline, crossline, noinline
  - [ ] out by, in by
  - [ ] interface delegation
  - [ ] lazy vs lateinit

### Architecture
  - [ ] MVVM
  - [ ] MVI 
  - [ ] MVP
  - [ ] SOLID
  - [ ] DRY
  - [ ] Composition vs inheritance
  - [ ] Clean architecture and usecases
  - [ ] Modularisation
  - [ ] Understand: 
        - Clear separation of concerns
        - Composability
        - Reusability
        - Tesatability
        - Single source of truth
        - Unidirection data/event flow

  #### Links
  https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design
  https://martinfowler.com/eaaCatalog/repository.html
  https://www.digitalocean.com/community/conceptual_articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design

### Android Architecture Components
  - [ ] ViewModel (How does it work)
  - [ ] LiveData
  - [ ] Lifecycle

### Views and Rendering
  - [ ] Activity/Fragment lifecycle
  - [ ] [View lifecycle](https://proandroiddev.com/the-life-cycle-of-a-view-in-android-6a2c4665b95e)
  - [ ] [Activity launch modes](https://inthecheesefactory.com/blog/understand-android-activity-launchmode/en)
  - [ ] Intents (Explicit vs Implicit) & Intent filters
  - [ ] Data sharing between activities, fragments, viewmodels.
  - [ ] View rendering
  - [ ] UI Thread & RenderThread
  - [ ] Threads while rendering
  - [ ] Inter process communication & Binders
  - [ ] Serialisation, Parcelables, SparseArrays
  - [ ] Surviving configuration change 

#### Links
https://developer.android.com/topic/libraries/architecture/saving-states.html
https://stackoverflow.com/questions/3323074/android-difference-between-parcelable-and-serializable
https://stackoverflow.com/questions/1392351/java-reflection-why-is-it-so-slow/1392379#1392379
  
### Lists
  - [ ] [RecyclerView internals](https://medium.com/android-news/anatomy-of-recyclerview-part-1-a-search-for-a-viewholder-404ba3453714)
  - [ ] DiffUtil
  - [ ] [RecyclerView prefetching](https://medium.com/google-developers/recyclerview-prefetch-c2f269075710)

### Images
  - [ ] Bitmaps
  - [ ] Bitmap Recycling
  - [ ] Image caching

### Memory
  - [ ] Memory allocation
  - [ ] Memory leaks

### IO
  - [ ] Concurency vs Parallelism
  - [ ] Multi-threading
    - [ ] Threads
    - [ ] Concurrent reads/writes
    - [ ] Handlers, HandlerThreads
    - [ ] ExecutorService, ThreadManager
    - [ ] Application process and Main thread
  
  #### Links
  https://www.digitalocean.com/community/tutorials/threadpoolexecutor-java-thread-pool-example-executorservice
  https://stackoverflow.com/questions/763579/how-many-threads-can-a-java-vm-support
  https://medium.com/@workingkills/understanding-the-renderthread-4dc17bcaf979
  https://developer.android.com/guide/components/processes-and-threads
  https://developer.android.com/topic/performance/threads
  https://dev.to/anuj/understanding-handler-looper-and-handler-thread-3anf
  https://developer.android.com/reference/android/os/Looper
  https://developer.android.com/reference/android/os/HandlerThread
  https://developer.android.com/reference/android/os/Handler
  https://developer.android.com/reference/android/os/MessageQueue
   
  - [ ] Kotlin Coroutines
    - [ ] One off events
    - [ ] Continuous events
    - [ ] Throttling in continous events
    - [ ] Cancellation policies
    - [ ] CoroutineScope, CoroutineContext, Parent Job+Child Job, CustomScopes
    - [ ] Lifecycle
    - [ ] Exceptions
    - [ ] Flow
    
  #### Links
  https://medium.com/microsoft-mobile-engineering/kotlin-coroutines-1c8e009cb711
  https://stackoverflow.com/questions/1934715/difference-between-a-coroutine-and-a-thread
  https://stackoverflow.com/questions/58489659/how-to-increase-kotlin-coroutines-dispatchers-io-size-on-android
  
   
  - [ ] RxJava
    - [ ] Observable design patterns
    - [ ] Operators, flatmap, map, zip, combineLatest
    - [ ] Backpressue strategies

### Background Ops
  - [ ] Foreground services
  - [ ] WorkManager
    - [ ] WorkManager internals
  - [ ] Bound Service
  - [ ] Push notifications and priority

### Data synchronisation
  - [ ] Sync strategy
  - [ ] Offline first
  - [ ] Sync conflict strategy

### Networking
  - [ ] OkHttp/Retrofit
  - [ ] Networking without OkHttp/Retrofit
  - [ ] Polling vs Server Push
  - [ ] Websockets
  - [ ] Grpc (https://www.infoq.com/articles/websocket-and-http2-coexist/)
  - [ ] Rest
  - [ ] Handling server errors
  - [ ] Network caching
  - [ ] Cache headers

### Data persistence
  - [ ] SQLlite performance
  - [ ] SQLite locking (https://www.sqlite.org/lockingv3.html)
  - [ ] ContentProviders
  - [ ] ContentProvider security
  - [ ] Room 
  - [ ] SQLite trasactions, and ACID.


## Stability
  
### Screen rendering
  - [ ] Time to first draw
  - [ ] Report fully drawn
  - [ ] Frame metrics API
  
### Application startup
  - [ ] Cold start
  - [ ] Warm start

#### Links
https://medium.com/androiddevelopers/app-startup-part-1-34f57b65cacd
https://medium.com/androiddevelopers/app-startup-part-2-c431e80d0df

### Crashing reporting/Debugging
  - [ ] Effectively debugging a crash

### Release
  - [ ] Feature flags
  - [ ] Release channels (alpha, beta, production)
  - [ ] Staged rollouts

### CI/CD
  - [ ] Jenkins
  - [ ] Github actions

### Build time
  - [ ] Gradle cache

## Testability
  - Testing ViewModels
  - Testing coroutines
  - Testing Repositories
  - Mocks & Stubs
  - Writing tests
  - Setup and tear down steps

#### Links
http://android-doc.github.io/preview/testing/performance.html

## Security

### Device

  - [ ] Require passcode
  - [ ] Root detection

### Network 

- [ ]  TLS
- [ ]  SSL Pinning
- [ ] Host verification
- [ ] Token
- [ ] Use SSL
- [ ] Use network security config
- [ ] How https works?

### Data 

 - [ ] ContentProviders (Don't export)
 - [ ] Encrypted files
 - [ ] Encrypted prefs
 - [ ] Encrypted tokens/keys
 - [ ] SMS
 - [ ] Store encrypted data, SQLCipher
 - [ ] Apply signature level permissions

### Application 

 - [ ] Code obfuscation
 - [ ] Require 2FA
 - [ ] Strong pincodes
 - [ ] App State Expectations like: VPN, Custom keyboards
 - [ ] Permissions
 - [ ] Library
 - [ ] WebView
 - [ ] Dynamic code loading
 - [ ] Implicit Intents
 - [ ] Apply signature level permissions

### Social engineering
  
## Team
- [ ] Code reviews & Empathy
- [ ] Mentorship and guidance
- [ ] Learning initiatives


## Product
- [ ] Product metrics
- [ ] Tracking success metrics
- [ ] Balancing business and engineering



